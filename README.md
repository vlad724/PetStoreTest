# Java-Selenium-Cucumber-Test-Framework-API

## Importante para evitar errores se debe instalar jdk 11 https://www.oracle.com/cl/java/technologies/javase/jdk11-archive-downloads.html y editar las variables de entorno JAVA_HOME con el directorio del jdk11

## Se debe incluir carpeta bin en resources dentro debe contener las carpetas apk/chromewin64/windows32/zap junto con los respectivos drivers



Framework para pruebas API con Selenium/Cucumber Codigo Java y Maven (Udemy 2024)

### Para correr pruebas Web usando la suite de TestNG


**`mvn clean test -DsuiteFile='ApiTestPetStoreRunner.xml'`**

**`mvn clean test -DsuiteFile='ApiTestPetStoreRunnerNoParams.xml'`**

### Para cambiar de cliente booker o petStore

#### Se debe modificar el archivo ApiTest.properties api.client = (nombre del cliente, booker o petStore) y api.version (v2 en caso de petstore o nada en caso de booker) y para videoGame hay que correr el proyecto y luego configurar



