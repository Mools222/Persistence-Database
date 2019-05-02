# Persistence-Database

Demonstration of how to persistet data to different databases.

## Requirements

### MySQL

Requirements:
1. The MySQL Connector/J library must be added to the project. (https://dev.mysql.com/downloads/connector/j/)
2. A database named "feedback" must be created and hosted at "localhost:3306". The username must be "root" and the password must be blank ("").
3. A table named "comments" must be added via the following SQL statement:
CREATE TABLE comments (
        id INT NOT NULL AUTO_INCREMENT,
        MYUSER VARCHAR(30) NOT NULL,
        EMAIL VARCHAR(30),
        WEBPAGE VARCHAR(100) NOT NULL,
        DATUM DATE NOT NULL,
        SUMMARY VARCHAR(40) NOT NULL,
        COMMENTS VARCHAR(400) NOT NULL,
        PRIMARY KEY (ID)
    );

### SQLite

Requirements:
1. The SQLite JDBC Driver must be added to the project. (https://bitbucket.org/xerial/sqlite-jdbc/downloads/)
