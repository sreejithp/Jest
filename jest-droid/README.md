#Jest Droid

Jest Droid is the basic Android port of [Jest](https://github.com/searchbox-io/Jest).
Compared to Jest, this port replaces Apache HTTP Client usages with [httpclient-android](https://hc.apache.org/httpcomponents-client-4.3.x/android-port.html) for Android SDK compatibility.

Jest is a Java HTTP Rest client for [ElasticSearch](http://www.elasticsearch.org).

ElasticSearch is an Open Source (Apache 2), Distributed, RESTful, Search Engine built on top of Apache Lucene.

Usage
---------------------
Simply add the dependency to your Gradle backed Android project.


    dependencies {
        compile 'io.searchbox:jest-droid:0.1.6'
    }
    

Thanks
---------------------
Thanks to [JetBrains](http://www.jetbrains.com/) for providing a license for [IntelliJ IDEA](http://www.jetbrains.com/idea/) to develop this project.


Copyright and License
---------------------

Copyright 2013 www.searchly.com

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in
compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is
distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and limitations under the License.
