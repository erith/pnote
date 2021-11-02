## openjdk 11 설치 ##
https://jdk.java.net/archive/

## neo4j 다운 ###
https://neo4j.com/download-center/#community

## 파워셸에서 ##
```powershell
.\bin\neo4j.ps1 install-service
.\bin\neo4j.ps1 start
.\bin\neo4j.ps1 uninstall-service
```

## agensgraph test ##
-e PGDATA=/var/lib/postgresql/data/pgdata \
-v /custom/mount:/var/lib/postgresql/data \

```sh
# 
sudo docker run -it -e POSTGRES_PASSWORD={PASS} -p 5432:5432 sorrell/agensgraph-extension

# terminal 실행
sudo docker exec -it bf7  /bin/bash
 
# psql 실행
psql --username=postgres
```
