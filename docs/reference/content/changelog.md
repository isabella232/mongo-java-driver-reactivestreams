+++
date = "2015-10-08T09:56:14Z"
title = "Changelog"
[menu.main]
  weight = 55
  pre = "<i class='fa fa-cog'></i>"
+++

## Changelog

Changes between released versions

### 1.13.1
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.13)
  * Updated MongoDB Driver Async to 3.12.2
  * Fix GridFSDownloadPublisher larger than 2GB files [JAVARS-227](https://jira.mongodb.org/browse/JAVARS-227)
  * Fix GridFSBucket.uploadFromPublisher completion when more the one element given in stream [JAVARS-224](https://jira.mongodb.org/browse/JAVARS-224)

### 1.13.0
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.13)

  * Updated MongoDB Driver Async to 3.12.0
  * Refine binary stream interchange in GridFS [JAVARS-222](https://jira.mongodb.org/browse/JAVARS-222)
  * Reintroduced plain String query hint [JAVARS-221](https://jira.mongodb.org/browse/JAVARS-221)

### 1.12.0
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.12)

  * Updated MongoDB Driver Async to 3.11.0
  * Add the ability to specify a pipeline to an update command [JAVARS-170](https://jira.mongodb.org/browse/JAVARS-170)
  * Support 'startAfter' option to the $changeStream stage [JAVARS-147](https://jira.mongodb.org/browse/JAVARS-147)
  * Support Client-side Field Level Encryption [JAVARS-130](https://jira.mongodb.org/browse/JAVARS-130)
  * Support mongos pinning for sharded transactions [JAVARS-127](https://jira.mongodb.org/browse/JAVARS-127)

### 1.11.0
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.11)

  * Updated MongoDB Driver Async to 3.10.0
  * Support Skipping in GridFS [JAVARS-138](https://jira.mongodb.org/browse/JAVARS-138)
  * Support running commands as aggregation	[JAVARS-141](https://jira.mongodb.org/browse/JAVARS-141)
  * The driver now natively supports TLS/SSL without netty [JAVA-3100](https://jira.mongodb.org/browse/JAVA-3100)

### 1.10.0
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.10)

  * Updated MongoDB Driver Async to 3.9.0

### 1.9.2
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.9.2)

  * Updated MongoDB Driver Async to 3.8.2 [JAVARS-115](https://jira.mongodb.org/browse/JAVARS-115)

### 1.9.1
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.9.1)

  * Updated MongoDB Driver Async to 3.8.1 [JAVARS-107](https://jira.mongodb.org/browse/JAVARS-107)
  * Auto generate build information [JAVARS-106](https://jira.mongodb.org/browse/JAVARS-106)

### 1.9.0
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.9)

  * Updated MongoDB Driver Async to 3.8.0
  * Transaction support [JAVARS-59](https://jira.mongodb.org/browse/JAVARS-59)
  * Added new count API [JAVARS-89](https://jira.mongodb.org/browse/JAVARS-89)

### 1.8.0
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.8)

  * Updated MongoDB Driver Async to 3.7.0
  * Support first() methods on all MongoIterable based Publishers [JAVARS-66](https://jira.mongodb.org/browse/JAVARS-66)
  * Add support for com.mongodb.MongoClientSettings [JAVARS-60](https://jira.mongodb.org/browse/JAVARS-60)
  * Resolve MongoDriverInformation incompatibility [JAVARS-58](https://jira.mongodb.org/browse/JAVARS-58)
  * Support ReplaceOptions in CRUD API [JAVARS-57](https://jira.mongodb.org/browse/JAVARS-57)
  * Allow configuration of batchSize on FindPublisher and AggregatePublisher [JAVARS-30](https://jira.mongodb.org/browse/JAVARS-30)


### 1.7.1
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.7.1)

  * Updated MongoDB Driver Async to 3.6.3 - Decrease likelihood of implicit session leak [JAVARS-55](https://jira.mongodb.org/browse/JAVARS-55)

### 1.7
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.7)

  * Updated MongoDB Driver Async to 3.6.0
  * MongoDB 3.6 support [JAVARS-41](https://jira.mongodb.org/browse/JAVARS-41)
    See the [what's new in 3.6 guide](http://mongodb.github.io/mongo-java-driver/3.6/whats-new/)

---

### 1.6
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.6)

  * Updated Reactive Streams to 1.0.1 [JAVARS-36](https://jira.mongodb.org/browse/JAVARS-36)
  * Updated MongoDB Driver Async to 3.5.0 [JAVARS-35](https://jira.mongodb.org/browse/JAVARS-35)
  * Deprecated AggregatePublisher#useCursor [JAVARS-34](https://jira.mongodb.org/browse/JAVARS-34)
  * Deprecate modifiers in FindPublisher and replace with properties [JAVARS-28](https://jira.mongodb.org/browse/JAVARS-28)

---

### 1.5
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.5)

  * Added Collation support to delete operations [JAVARS-27](https://jira.mongodb.org/browse/JAVARS-27)

---

### 1.4
[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.4)

  * Updated MongoDB Driver Async to 3.4.2
  * Added GridFS support [JAVARS-23](https://jira.mongodb.org/browse/JAVARS-23)
  * Added `MongoClients.getDefaultCodecRegistry()` [JAVARS-16](https://jira.mongodb.org/browse/JAVARS-16)
  * Added a static factory method to MongoClients to taking an already constructed async.client.MongoClient [JAVARS-26](https://jira.mongodb.org/browse/JAVARS-26)

---

### 1.3

[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.3)

  * Updated MongoDB Driver Async to 3.4.0
  * Added Collation support [JAVARS-21](https://jira.mongodb.org/browse/JAVARS-21)
  * Added support for views [JAVARS-22](https://jira.mongodb.org/browse/JAVARS-22)
  * Added support for extending handshake metadata [JAVARS-20](https://jira.mongodb.org/browse/JAVARS-20)

---

### 1.2

[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARS%20AND%20fixVersion%20%3D%201.2)

  * Updated MongoDB Driver Async to 3.2.0
  * Added support for MongoDB 3.2.0 features

---

### 1.1 

  * Updated MongoDB Driver Async to 3.1.0
  
    Simplified the driver by using the new `com.mongodb.async.client.Observable` and mapping to `Publisher`

