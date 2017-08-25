proto-objects
---
artifact with all protobuf generated java files

Execute `./gradlew clean cloneProtoDefRepository publishToMavenLocal` for local installation with git cloning

Execute `./gradlew clean publishToMavenLocal` for dockerfile building.
 **Warning** - you should have proto definitions installed manually into `src/main/proto` folder