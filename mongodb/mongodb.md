# MONGODB

## Url de instalación

https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/

## Comando básicos

* Start MongoDB.

```shell
sudo systemctl status mongod
```

* Verify that MongoDB has started successfully.

```shell
sudo systemctl status mongod
```

- Stop MongoDB.

```shell
sudo systemctl stop mongod
```

- Restart MongoDB

```shell
sudo systemctl restart mongod	
```

- Begin using MongoDB

```shell
mongo
```

## Uninstall mongodb

- Stop MongoDB

```shell
sudo service mongod stop
```

- Remove Packages

```shell
sudo apt-get purge mongodb-org
```

- Remove Data Directories

```shell
sudo rm -r /var/log/mongodb
sudo rm -r /var/lib/mongodb
```