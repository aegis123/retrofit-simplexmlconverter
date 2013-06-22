# retrofit-simplexmlconverter

Converter implementation for Square's [retrofit][1] library which uses [Simple XML][2]
for serialization and deserialization of entities.



## Usage

Using the converter is as simple as creating your RestAdapter as usual and calling setConverter(...) with an instance of SimpleXmlConverter:

```java
RestAdapter restAdapter = new RestAdapter.Builder()
    .setServer(...)
    .setConverter(new SimpleXmlConverter())
    .build();
```

Optionally you can provide your own *Serializer* to the constructor.


If you are building with ant, [download][3] the Simple XML library and add it to your <code>libs</code> folder manually.



## Download

Download [the latest JAR][4] or grab via Maven:

```xml
<dependency>
    <groupId>com.mobprofs</groupId>
    <artifactId>retrofit-simplexmlconverter</artifactId>
    <version>(insert latest version)</version>
</dependency>
```


## License


    Copyright 2013 Mobile Professionals

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


 [1]: http://square.github.io/retrofit/
 [2]: http://simple.sourceforge.net/
 [3]: http://simple.sourceforge.net/download.php
 [4]: http://repository.sonatype.org/service/local/artifact/maven/redirect?r=central-proxy&g=com.mobprofs&a=retrofit-simplexmlconverter&v=LATEST


[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/ccc52c0234f155e4c3e851ece680b4aa "githalytics.com")](http://githalytics.com/mobile-professionals/retrofit-simplexmlconverter)