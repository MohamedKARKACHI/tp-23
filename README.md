# Architecture Microservices avec Consul

Configuration Docker pour une architecture microservices avec découverte de services via Consul.

## Services

- **Consul** - Registre de services
- **MySQL** - Base de données
- **Service Client** - API de gestion des clients
- **Service Voiture** - API de gestion des véhicules
- **Gateway** - Passerelle API

## Démarrage

```bash
docker-compose up -d
```

## Ports

| Service | Port |
|---------|------|
| Consul UI | 8500 |
| MySQL | 3309 |
| Service Client | 8088 |
| Service Voiture | 8082 |
| Gateway | 8888 |

## Arrêt

```bash
docker-compose down
```
# tp-23


## Author

- **Karkachi Mohamed**
