esapi-hackathon
===============

Welcome to the ESAPI 3.x Hackathon!

# Criteria for Judging
- Community Need
- Code Quality
- Testability
- Documentation


# ESAPI-Core Maven Dependency

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

# Tools and Applications

http://esapi.ci.cloudbees.com -- Jenkins

http://repository-esapi.forge.cloudbees.com -- Maven Repository / File Hosting

https://www.owasp.org/index.php/Category:OWASP_Enterprise_Security_API -- OWASP Wiki

