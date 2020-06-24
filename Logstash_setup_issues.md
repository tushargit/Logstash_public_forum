Logstash setup issue
=======================================
###  An exception happened when converging configuration {:exception=>ArgumentError, :message=>"Setting \"modules.cli\" hasn't been registered"
**Sol**

Delete all empty conf files or directory as defined in pipeline.yml as logstash cannot load empty configuration string.
