# ClusterPoint Cloud API Service for Sails Framework

## Using in sails

Place the CPSDB.js inside `/api/services/`. Since services are global in sails, it is possible to call it from anywhere inside project root folder. 


##### Dependency

```
$ npm install cps-api --save
```

##### Code inside controllers or models

```
var cps = CPSDB.init('database'); // Parameter is the name of database.
```
You have to call init function to connect to each database.


### Syntax

#### cps.insert( object, callback );

#### cps.update( object, callback );

#### cps.replace( object, callback );

#### cps.partialReplace( object, callback );

#### cps.delete( object, callback );

#### cps.search( array, callback ); // Array example: [{ id: uid }]

#### cps.lookup( array,callback );

#### cps.retrieve( array, callback );

#### cps.listLast( integer, integer, callback );

#### cps.listPaths( callback );

#### cps.status( callback );

#### cps.clear( callback );

#### cps.reindex( callback );


[API Reference](http://docs.clusterpoint.com/wiki/Main_Page)


[API Code Sample](http://docs.clusterpoint.com/examples/#/Node.js/connection)

***

![image_squidhome@2x.png](http://sailsjs.org/images/bkgd_squiddy.png)