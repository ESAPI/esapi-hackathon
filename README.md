esapi-hackathon
===============

Repository for the ESAPI Hackathon at AppSecUSA

ESAPI-Core Maven Dependency

```xml
<repositories>
  <repository>
    <id>esapi-snapshots</id>
    <name>ESAPI 3.x Snapshot Repository</name>
    <snapshots>
      <enabled>true</enabled>
      <updatePolicy>never</updatePolicy>
      <checksumPolicy>fail</checksumPolicy>
    </snapshots>
    <url>http://repository-esapi.forge.cloudbees.com/snapshot/</url>
  </repository>
<repositories>

<dependency>
  <group>org.owasp.esapi</group>
  <artifact>esapi</artifact>
  <version>3.0-SNAPSHOT</version>
</dependency>
```
