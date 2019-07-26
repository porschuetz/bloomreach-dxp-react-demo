Running Locally
===============

This project uses the Maven Cargo plugin to run Essentials, the CMS and site locally in Tomcat.
From the project root folder, execute:

    mvn clean verify
    mvn -P cargo.run

Logs are located in target/tomcat9x/logs

Starting the React Single Page Application
==========================================

The SPA is delivered via http://localhost:8081
    
    cd frontend
    yarn install
    yarn serve
