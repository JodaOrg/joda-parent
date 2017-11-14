Joda-Parent
-----------

Joda-Parent is the parent pom.xml for other Joda.org projects.

It is licensed under the business-friendly [Apache 2.0 licence](http://www.joda.org/joda-collect/license.html).


### Release process

* Update version (pom.xml)
* Commit and push
* `mvn clean deploy -Doss.repo -Dgpg.passphrase=""`
* Release project in [Nexus](https://oss.sonatype.org)
