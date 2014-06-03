Using the Service Account App Engine Sample
==============================================

Browse Online
-------------

The main file is [StorageSample.java](TBD). 

Get a Service Account
---------------------

See the instructions at https://developers.google.com/storage/docs/xml-api-java-samples
for setting up a service account.

Checkout Instructions
---------------------

**Prerequisites:** install the latest version of [Java](http//java.com) and [Maven](http://maven.apache.org/download.html). You may need to set your `JAVA_HOME`.

You must also be able to work with a GitHub repository (see e.g.,
https://help.github.com/articles/set-up-git).

    cd [someDirectory]
    git clone https://github.com/GoogleCloudPlatform/cloud-storage-docs-xml-api-examples.git
    cd storage-serviceaccount-appengine-sample
    mvn clean package

To enable logging of HTTP requests and responses (highly recommended when 
developing), please take a look at logging.properties.

Running and Deploying Your Application from the Command Line
------------------------------------------------------------

To run your application locally on a development server:

    mvn appengine:devserver

