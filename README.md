# Ayuda 

Carga enviroment desde un archivo .env con ayuda de github.com/joho/godotenv



### Ejemplo

Para cargar los env si estas en dev y no afectar prod

```go
env_cm.GetEnvFile()
```

Solo carga el archivo si

os.Getenv("ENV") es diferente de "prod"
