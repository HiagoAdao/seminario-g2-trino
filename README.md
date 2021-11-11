# seminario-g2-trino

### Instalção Docker

docker run -d --name trino-trial trinodb/trino

### Execução Container

docker start trino-trial<br>
docker exec -it trino-trial trino

### Comands Trino

> help - Comandos para trino para navedação ate os dados

> show catalogs; <br>
> show schemas from system;<br>
> show tables from system.jdbc;<br>
> show columns from system.jdbc.catalogs;<br>
> show columns from system.jdbc.attributes;<br>

