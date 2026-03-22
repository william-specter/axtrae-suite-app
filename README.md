Axtrae Open Suite
================================

Axtrae Open Suite reduces the complexity and improve responsiveness of business processes. Thanks to its modularity, you can start with few features and  then activate other modules when needed.

Axtrae Open Suite includes the following modules :

* Customer Relationship Management
* Sales management
* Financial and cost management
* Human Resource Management
* Project Management
* Inventory and Supply Chain Management
* Production Management
* Multi-company, multi-currency and multi-lingual

Axtrae Open Suite is built on top of a customized version of the Axelor Open Platform.


Installation
================================

To compile and run from source, you only need to clone this repository. All modules are included.

```bash
$ git clone git@github.com:william-specter/axtrae-suite-app.git
$ cd axtrae-suite-app
```

### Running the application

Once the project is cloned, you can run the application using the Gradle wrapper:

```bash
# On Windows
.\gradlew.bat run

# On Linux/macOS
./gradlew run
```

This will start the application, and it should be available at `http://localhost:8080`. Please ensure you have a PostgreSQL database configured as specified in `src/main/resources/axtrae-config.properties`.
