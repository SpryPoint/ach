ach
===

A library for working with ach/nacha files

Deployment configuration
===========================
To deploy to github maven repo, save the following to ~/.m2/settings.xml and use appropriate $GITHUB_MVN_REPO_OWNER and $GITHUB_PERSONAL_ACCESS_TOKEN.
```xml
<settings xmlns="http://maven.apache.org/SETTINGS/1.0.0"
      xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
      xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0
                          http://maven.apache.org/xsd/settings-1.0.0.xsd">
    <localRepository/>
    <interactiveMode/>
    <usePluginRegistry/>
    <offline/>
    <pluginGroups/>
    <servers>
        <server>
            <id>github</id>
            <username>$GITHUB_MVN_REPO_OWNER</username>
            <password>$GITHUB_PERSONAL_ACCESS_TOKEN</password>
        </server>
    </servers>
    <mirrors/>
    <proxies/>
    <profiles/>
    <activeProfiles/>
</settings>
```
