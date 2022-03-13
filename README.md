# docker

Docker compose file for backend infra (so far mongodb container)


Start services:
```
docker compose up
```

Shutdown services:
```
docker compose down
```

**IMPORTANT**: setup env. var. **DB_FOLDER** in **.env** file if you are running on linux.

Are you lazy windows bitch? Then use **up.bat** & **down.bat** script in scripts folder ;) **DB_FOLDER** is configured in **up.bat**.