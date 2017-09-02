# Language_Time
[ ![Download on bintray](https://api.bintray.com/packages/adetuyitolu/maven/crev-NgTime/images/download.svg) ](https://bintray.com/adetuyitolu/maven/crev-NgTime/_latestVersion)

A library that converts Time to its equivalent basic local Nigeria languages (Yoruba, Hausa and Igbo)

## Setting up

### Dependency

*  Maven
```groovy
<dependency>
  <groupId>com.crevation.NgTime</groupId>
  <artifactId>crev-NgTime</artifactId>
  <version>0.1</version>
  <type>pom</type>
</dependency>
```

*  Gradle
```groovy
compile 'com.crevation.NgTime:crev-NgTime:0.1'
```

## Usage

```java

	//instatntiate the language of your choice, Yoruba in this case
 	Time yoruba = new Yoruba();

	//you can as well use other languages available
        Time igbo = new Igbo();
        Time hausa = new Hausa();

        String yorubaTime = yoruba.getTime("4:00");
        String currentTime = yoruba.getCurrentTime();
        String calendarTimeyoruba.getTime(Calendar.getInstance());
        String dateTime =yoruba.getTime(new Date());   
```

## License

    Copyright 2017 Adetuyi Tolu Emmanuel

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

## Contributions
