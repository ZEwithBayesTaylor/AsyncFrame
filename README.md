# AsyncFrame Instruction

## Team Member
Er Zhao, Ling Liu

## Init mysql

```bash
#
# init mysql
docker compose up -d
# check mysql docker
docker exec -it async-flow-db /usr/bin/mysql -uroot -proot@2023 -D asyncflow -e "show tables;"
```
