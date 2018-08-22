- Start grakn server

  - Stop existing redis-server at 6379
    `sudo service redis-server stop`
  - Start grakn server
    `sudo ./<path to grakn>/grakn server start`

- Clean grakn data and logs

  - Stop grakn
    `sudo ./<path to grakn>/grakn server stop`
  - Clean grakn
    `sudo ./<path to grakn>/grakn server clean`

- Load new schema

  `./graql console -f ~/<path to schema>/schema.gql -k <keyspace name>`
