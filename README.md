# account-service

Para ejecutar el proyecto en forma local basta con ejecutar el siguiente comando:

```bash
mvn spring-boot:run
```

## Testing

* POST - http://localhost:8080/accounts/ 
```bash
     {
        "username": "gonzalo",
        "password": "12345678"
     }
```

* GET - http://localhost:8080/uaa/user/current
```bash
    Usar Authorization header -> Bearer con token devuelvo por POST anterior
```
