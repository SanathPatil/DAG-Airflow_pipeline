## Airflow DAG to read data from raw csv files, transform and write it to a SQLite database

### Docker image is used to set up and run Airflow and SQLite db
To initialize and update Airflow db:
```
docker-compose up airflow-init
```
Run Docker:
```commandline
docker-compose up
```

Note: Airflow DAG can be viewed on webserver specified in the docker file ```localhost:8081/```