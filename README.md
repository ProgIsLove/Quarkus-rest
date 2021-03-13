# Quarkus-rest project

This project uses Quarkus, the Supersonic Subatomic Java Framework.

If you want to learn more about Quarkus, please visit its website: https://quarkus.io/ .

## Working with Quarkus in your IDE

### Prerequisites
The following items should be installed in your system:
* Java 8 or newer.
* Git command line tool (https://help.github.com/articles/set-up-git)
* Your preferred IDE
  * Eclipse
  * IntelliJ IDEA

1) On the command line
    ```
    git clone https://github.com/ProgIsLove/Quarkus-rest.git
    ```
2) Open terminal
    ```shell script
    ${yourPath}/quarkus-rest>mvnw compile quarkus:dev
    ```
3) Visit http://localhost:8080/hello in your browser.
 
4) Open Postman or Insomnia rest and try this command
    ```
    GET localhost:8080/person
    
    GET localhost:8080/person/1
    
    GET localhost:8080/person/name/${fistName}
    
    GET localhost:8080/person/name/${firstName}/${lastName}
    
    POST localhost:8080/person => in Body section, tick raw, select JSON and write 
    
    {
      "firstName": "name",
      "lastName": "lastName"
    }
    
    ```
 <img alt="section" src="https://imgur.com/BWsGDZo.png">
    
 5) enjoy <3






