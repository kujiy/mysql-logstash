# mysql-logstash-example

## How to Use
1. Update `config/logstash.yml` depends on your elasticsearch server
1. Update `config/my-import.conf` depends on your mysql/elasticsearch server
1. Start container

    ```
    $ docker-compose up -d
    ```
1. See whether your data was imported on `Discover` section of your kibana

