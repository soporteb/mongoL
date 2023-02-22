# connect to container

```sh
docker-compose exec my-dbName bash
```

# connect with mongosh
```sh
mongosh ""
```

# vemos los archivos
```sh
show dbs
show collections
```

# consulta
```sh
use("enei_store")
db.productos.find()
```