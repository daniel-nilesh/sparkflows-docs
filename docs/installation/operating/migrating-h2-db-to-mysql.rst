Migrating from H2 DB to MySQL
=============================

Fire Insights comes with an embedded H2 DB.

There are times when we start with the embedded H2 DB, but then want to want to an MySQL.

Below are the steps for migrating the data from H2 DB to MySQL.

Migrate H2 DB data to MySQL from executable jar file.
-----------------------------------------------------

- Run MySQL script to generate fire database and tables in MySQL.
- Open the command prompt.
- Go to the `migratedb` folder inside `fire-ui`.
- Run command - ``java -jar migratedb.jar <MySQL JDBC URL> <MySQL user name> <MySQL password>``
