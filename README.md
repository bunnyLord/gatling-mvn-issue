# Gatling Maven Issue

This project is meant as an example material for Gatling mvn issue when trying to run the simulation from outside of the Gatling project.

gatling-mvn-issue $ mvn clean test

SUCCESS

gatling-mvn-issue $ cd ..
parent $ mvn -f gatling-mvn-issue/pom.xml clean test

[ERROR] No simulations to run
[ERROR] Failed to execute goal io.gatling:gatling-maven-plugin:2.1.7:execute (default) on project gatling-mvn-issue: Gatling failed. No simulations to run -> [Help 1]