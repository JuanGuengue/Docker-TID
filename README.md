## Infraestructura

| Rol | IP Privada | IP Pública |
|-----|-----------|------------|
| Master | 10.0.1.107 | 3.145.113.6 |
| Worker 1 | 10.0.2.22 | NO_IP_PUBLICA |
| Worker 2 | 10.0.2.146 | NO_IP_PUBLICA |
| Worker 3 | 10.0.2.48 | NO_IP_PUBLICA |

## Servicios

| Servicio | Puerto | Servidor |
|---------|--------|---------|
| Airflow Webserver | 8080 | Master |
| Flower | 5555 | Master |
| RabbitMQ Management | 15672 | Master |
| PostgreSQL | 5432 | 51.222.142.204 |
