JATEToolkit
====
The mavenized version of [JATEToolkit](https://code.google.com/p/jatetoolkit/).

To build a self-contained JAR file with all the dependencies:

    mvn clean package

To run the TermEx (Term Extractor):

    java -Xmx512m -jar ./target/jate-2.0Alpha-SNAPSHOT-jar-with-dependencies.jar \
        /home/emre/data/belga/input \
        /home/emre/code/workarea/jate/resource/bnc_unifrqs.normal \
        /home/emre/data/belga/output