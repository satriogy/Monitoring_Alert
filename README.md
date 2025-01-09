# Monitoring
Prometheus, Node-Exporter, Grafana

Struktur 

monitoring/
├── server-master/
│   ├── docker-compose.yml
│   └── prometheus.yml
│
├── server-agent/
│   └── docker-compose.yml
│
├── grafana/
│   └── provisioning/
│       ├── dashboards/
│       │   └── default.json
│       └── datasources/
│           └── datasource.yml
└── README.md
