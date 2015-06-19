Simple Maven project that allows to bundle the Spark-Cassandra connector *without* rebuilding it. It will pull the connector and its dependencies from Maven Central and package an uber jar that you can deploy on a Spark cluster.

Usage:

    $ mvn package

To build a specific version:

    $ git checkout spark-cassandra-1.x
    $ mvn package
