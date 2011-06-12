Multicore Solr Server example
=============================

This is a **multicore** [Solr Server](http://wiki.apache.org/solr/) sample instance with two cores and a basic config for each one. 
You must add declarations for each field you need to the schema of the core the field belongs to. Edit `multicore/core/core1/schema.xml` 
and `multicore/core/core2/schema.xml`

Installation / Usage
--------------------

 * Clone this repository or just download your prefered tagged version.

 * Run it:

    cd solr-server-multicore
    java -Dsolr.solr.home=multicore -server -jar start.jar

 * Go http://localhost:8983/solr/ y play with it using the Solr Admin Interface.
