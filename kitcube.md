Container
------------

**How to connect to the servers?**

Connecting to the kitcube container through ```dyndns.info``` with different ports *22*, *23*, *24* 
```
ssh -p [22,23,24] cube@kitcube.dyndns.info
```
will directly log on to different servers *imk-data1*, *imk-db1* and *imk-adei1*.  For debugging ADEI or status display, a tunnel could be built
```sh
ssh -L 8024:imk-adei1:80 cube@kitcube.dyndns.info
```

