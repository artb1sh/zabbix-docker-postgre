# zabbix-docker-postgre

Steps for running
1. Put the configuration in a file and save with name docker-compose.yml. To keep separate create folder with name you want and put the compose file in that folder. This folder you can use for running docker-compose.
2. Open Terminal and cd to folder you created and then run command

```
docker-compose up -d
```

or if you prefer logs to be shown, then

```
docker-compose up
```

3. Now access Zabbix UI at port 8090(replace this port with your port if you have changed in above compose file). Open this url in browser

```
http://localhost:8090
```

4. Now login by entering username , password for default Admin user with credentials.

```
username : Admin

password: zabbix
```

5. Now you are setup and will reach dashboard with various tiles for information.
