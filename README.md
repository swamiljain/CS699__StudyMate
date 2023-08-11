# CS699__StudyMate

First create your own enviroment

`$ pip install -r requirements.txt`

You will get error here for **psycopg2**

Run this command after installing postgres
`sudo apt-get install --reinstall libpq-dev`




## Instructions for postgres
### Installation Link
`https://www.postgresql.org/download/linux/ubuntu/`

### Some Commands to start postgres
- changing the user
``` $ sudo -i -u postgres```

- running psql
  ``` $ psql```
- exit from psql shell
  `>> \q`

-Create dB
`createdb my_pgdb`

-Switching to database
`psql -d my_pgdb`

-Getting current info 
`\conninfo`

### Installing pgadmin
https://www.pgadmin.org/download/pgadmin-4-apt/

