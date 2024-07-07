# RDS-DB-read-replicas
RDS Database with read replicas

## Install postgresql and

```bash
sudo apt-get install -y postgresql
```
## Connect from EC2

```bash
psql --host=<Endpoint> --port=5432 --username=awsuser --password --dbname=mypgdb
```