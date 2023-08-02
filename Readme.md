# Mysql and PhpMyAdmin container

<div id="header" align="center">

  <img src="./media/docker-logo.png" width="100"/>

</div>


## how to run: 

After cloning the repository, open the **docker-compose.yml** file and set a password for you in the "**mysql_db**" section and save the file. 

To run for the first time, use this command: 

```
docker-compose up --build
```

## how to stop:

Use **ctrl+c** to stop.

----
Once installed, whenever you need to initialize containers, use:

```
docker-compose up
```

## Login on PhpMyAdmin: 

Access http://localhost:9090/

* **Username**: root
* **Password**: Can be found on **docker-compose.yml** in the  "**mysql_db**" section
* **Server name**: The server's name is 'mysql_db' and can be found or changed in the file **docker-compose.yml**
