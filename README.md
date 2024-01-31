# pulsar-docker

## Apache Pulsar

```
docker compose up -d pulsar
```

## Apache Pulsar Manager

```
docker compose up -d pulsar-manager
```

goto to [http://localhost:9527](http://localhost:9527) and authenticate with user: admin, password: apachepulsar

## Apache Pulsar (users and passwords)

```
chmod u+x pulsar-manager.sh
./pulsar-manager.sh

```

## Consumer terminal

```
docker compose up python-app-consumer
```

## Producer terminal

```
docker compose up python-app-producer
```
