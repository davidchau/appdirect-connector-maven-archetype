# appdirect-connector-maven-archetype
archetype project to bootstrap an AppDirect connector

## How to install
`mvn clean install`

## How to use
```mvn archetype:generate \
-DarchetypeArtifactId=appdirect-connector-maven-archetype \
-DarchetypeGroupId=com.appdirect.sdk.connector \
-DarchetypeVersion=1.0-SNAPSHOT \
-DgroupId=<your.project.group.id> \
-DartifactId=<your-project-name>
