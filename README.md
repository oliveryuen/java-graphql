# java-graphql
Java GraphQL

#
```bash
# archetype generate
mvn archetype:generate -DarchetypeArtifactId=maven-archetype-webapp -DgroupId=com.howtographql.sample -DartifactId=hackernews-graphql-java -Dversion=1.0-SNAPSHOT
# start (at where pom.xml resides)
mvn jetty:run
```

http://localhost:8080/graphql?query={allLinks{url}}

# In-Browser IDE
https://github.com/graphql/graphiql
