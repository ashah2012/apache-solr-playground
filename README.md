# apache-solr-playground

All learning resources for Apache Solr. 

## Important scripts

Start Solr in cloud mode :

* solr.cmd start -e cloud

Starting individual nodes :

* start -cloud -p 8983 -s "example/cloud/node1/solr"
* start -cloud -p 7574 -s "example/cloud/node2/solr" -z localhost:9983

Stoping all nodes :

* solr stop -all

Posting data for indexing (run from SOLR HOME): 

* java -jar -Dc=techproducts -Dauto example\exampledocs\post.jar example\exampledocs\*

## Links to Resources

* [Launch Solr in Cloud Mode](http://lucene.apache.org/solr/guide/7_2/solr-tutorial.html#launch-solr-in-solrcloud-mode)
* [Solr Glossary](http://lucene.apache.org/solr/guide/7_2/solr-glossary.html#shard)
* [Solr Script Reference](http://lucene.apache.org/solr/guide/7_2/solr-control-script-reference.html#solr-control-script-reference)
* [Solr Advance Searching](http://lucene.apache.org/solr/guide/7_2/searching.html#searching)
* [Dzone RefCard](https://dzone.com/storage/assets/3879-rc120-010d-solr_0.pdf)
