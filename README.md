# Category Service System API

# Project Description
The Category Service API app is a service level api that encapsulates category data from the Caliber API. Users can get all categories from the Caliber API.

# BUILT WITH
- Mulesoft
- MUnit
- Log4J
- Maven
- Anypoint Platform
- Anypoint Studio
- REST

# Getting Started
- Go to ${users.home}/m2 folder:
- Rename or delete repository
- Rename settings.xml
- git clone https://github.com/Caliber-Mulesoft/category-service-api.git
- Import project CategorySystemAPI into Anypoint Studio (the folder containing the project has the same name).
- Deploy to CloudHub (Anypoint Platform)
- Please refer to the SETUP document for more detailed installation steps.

# PREREQUISITES
- Anypoint platform
- Anypoint studio 7.8.0
- OpenJDK 8
- Embedded Maven
- HTTP connector 1.5.24
- APIkit 1.5.1

# USAGE EXAMPLES
GET All Categories: Retrieves a list of assessment category objects. /category
 Example Output:
 ```
 [
  {
    "active": true,
    "categoryId": 90,
    "skillCategory": "Unix"
  },
  {
    "active": false,
    "categoryId": 8,
    "skillCategory": "Necromancy"
  }
]
 ```

GET category by id: Retrieves assessment category object based on its unique ID. /category/{id}
URI Parameter: 'id' Required

Example Output
```
[
  {
    "active": true,
    "categoryId": 90,
    "skillCategory": "Unix"
  }
]
```

# AUTHORS
- Christopher Proutt
- Diego Franchi
- Daniel Beintema
- Kevin Novikov
