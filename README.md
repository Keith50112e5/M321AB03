## Aufgabe 2

#### Services:

| Service             | Link                                                    |
| ------------------- | ------------------------------------------------------- |
| Prometheus          | [localhost:9090](http://localhost:9090)                 |
| Prometheus-Metriken | [localhost:9323/metrics](http://localhost:9323/metrics) |
| Grafana             | [localhost:3000](http://localhost:3000)                 |

#### Grafana-Benutzerdaten:

Benutzername: `admin`
Passwort: `admin`

#### Docker Befehle

Docker starten:
`docker compose -f ./compose.json up -d`
oder
`docker compose up -d`

Docker beenden:
`docker compose down`
