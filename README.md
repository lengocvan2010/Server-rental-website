# Server-rental-website


## Description
    This website provides a server rental system. With admin can manage packages, package statistics and user statistics. 
    Users can choose, register for packages, and cancel renewals. Website uses stripe for online payments

## Prepare the environment
    MySQL: Version 8.0.33
    Java:  version 17.0.7

## Install project

    1. Clone project from gitlab
            Step 1: From a folder, right click and open Git Bash

            Step 2: Connect to gitlab account with two command lines
                git config --global user.name "Your GitLab Username"
                git config --global user.email "your-email@example.com"

            Step 3: Clone project
                In Git Bash, uses this command to clone project  from gitlab
                git clone [repository_url]

    2. Import code in the IDE
           Open the folder you just cloned from gitlab in the IDE

    3. Prepare database
           Open file application.properties and SpringSecurityApplication.java
                Check URL, Username, Password, Name of Database and Port
                example:
                    spring.datasource.url=jdbc:mysql://localhost:<port>/<name of database>
                    spring.datasource.username=<username>
                    spring.datasource.password=<password>
                    spring.datasource.driverClassName=com.mysql.cj.jdbc.Driver
    4. Run Application
           Run this command in terminal: mvnw spring-boot:run

## Use program
    Login with account in database
        - Admin: van@gmail.com/111115
        - User: vu@gmail.com/111115

