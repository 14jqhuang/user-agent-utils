user-agent-utils
================

Utilities for processing user-agent strings. Can be used to handle http requests in real-time or to analyze log files.

http://haraldwalker.github.com/user-agent-utils/

New in Version 1.8
------------------

* Option just to check just for a given collection of browsers or operating systems
* Updated Chrome, Firefox and Safari detection to include the latest versions
* Minor code optimizations

Javadoc
-------
http://haraldwalker.github.com/user-agent-utils/javadoc/

Maven
-----

Include our github repository in your pom.xml:
```xml
<repository>
  <id>bitwalker.user-agent-utils.mvn.repo</id>
  <url>https://raw.github.com/HaraldWalker/user-agent-utils/mvn-repo/</url>
  <!-- use snapshot version -->
  <snapshots>
     <enabled>true</enabled>
      <updatePolicy>always</updatePolicy>
   </snapshots>
</repository>
```
