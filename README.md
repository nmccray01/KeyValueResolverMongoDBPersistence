# KeyValueResolverMongoDBPersistence

<h4>Important</h4>

All future versions of this package will be released in a new repository: [java-library-key-value-resolver-mongodb-persistence](https://github.com/nitrobox/java-library-key-value-resolver-mongodb-persistence)

This repository will be archived to keep older versions of this package available.

---

A persistence for KeyValueResolver into a MongoDB using Spring Data

The project that wants to use this persistence needs to add a dependency to 
```org.springframework.boot:spring-boot-starter-data-mongodb``` and activate
the Mongo Repository by using the annotation:
```@EnableMongoRepositories("com.nitrobox.keyvalueresolver.mongodbpersistence")```
