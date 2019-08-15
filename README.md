### fugue
---
https://bitbucket.org/atlassian/fugue

```java
import io.atlassian.fugue.converters.ScalaConverters._
```

```sh
mvn clean install
mvn clean install javadoc:javadoc
mvn formatter:format
mvn scalariform:format
mvn verify
mvn clean clover:setup test clover:aggregate clover:clover
compile 'io.atlassian.fugue:fugue:4.7.1'
```

```
<dependencies>
  <dependency>
    <groupId>io.atlassian.fugue</groupId>
    <artifactId>fugue</artifactId>
    <version>4.7.1</version>
  </dependency>
</dependencies>

```
