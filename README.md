#Maven Repository

Add the releases and snapshot repositories to your Maven settings.xml or to your projects pom.xml.

    <repositories>
        <repository>
            <id>scandio-public-releases</id>
            <name>Scandio Public Releases Repository</name>
            <url>https://github.com/scandio/mvn-repo/raw/master/releases</url>
        </repository>
        <repository>
            <id>scandio-public-snapshots</id>
            <name>Scandio Public Snapshots Repository</name>
            <url>https://github.com/scandio/mvn-repo/raw/master/snapshots</url>
        </repository>
    </repositories>