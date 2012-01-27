!SLIDE bullets small incremental
* Scalable 
* Highly-available 
* Networked key/value storage
* REST API
* JSON
* MapReduce

!SLIDE center
## That doesn't sound like a big hit

![CouchDB](ext/couchdb-logo1.png)

!SLIDE
# Riak != CouchDB

!SLIDE center
![Values](ext/13661582.jpg)
(+ metadata (and links too!))

!SLIDE center
![Keys](ext/key.png)

!SLIDE center code
![Bucket](ext/bucket.jpg)
<obj/ect/url/bucket,tag,keep?/...>

!SLIDE center
## It's a graph!
![Graph](ext/graph.jpg)

!SLIDE bullets incremental
* partitions &#8834; ring
* partitions &#8776; vnode
* node &#8835; vnode
* node &#8838; cluster

!SLIDE center
![Riak](ext/riak-transparent-larger.png)
(schematic diagram for you)

!SLIDE 
# And RESTful?

!SLIDE bullets incremental code
* GET /riak/bucket/key
* PUT /riak/bucket/key
* POST /riak/bucket
* DELETE /riak/bucket/key
