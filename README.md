# golang-mybank

## tech stack

- gin
- postgres
- k8s+aws
- gRPC

## features

- Create and manage bank accounts.
- Record all balance changes to each of the accounts.
- Perform a money transfer between 2 accounts.

## Notes

### Working with database

```bash
brew install golang-migrate
mkdir -p db/migration
migrate create -ext sql -dir db/migration -seq init_schema

# 接下来的操作竟然是手动复制up和down的sql语句...😅 
```
