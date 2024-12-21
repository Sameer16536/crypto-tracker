crypto-tracker/
├── cmd/                 # Command-line applications (e.g., main API server).
│   └── main.go
├── internal/            # Internal application code.
│   ├── handlers/        # API handlers for routes.
│   │   ├── alerts.go
│   │   ├── portfolio.go
│   │   └── prices.go
│   ├── services/        # Business logic (fetching data, etc.).
│   │   ├── coingecko.go
│   │   ├── alerts.go
│   │   └── websocket.go
│   ├── db/              # Database logic.
│   │   ├── mongo.go
│   │   └── models.go
│   └── websocket/       # WebSocket logic.
│       └── websocket.go
├── pkg/                 # Shared utilities and libraries.
│   └── logger/          # Logging utilities.
│       └── logger.go
├── configs/             # Configuration files (e.g., .env).
│   └── config.go
├── go.mod               # Go module file.
├── go.sum               # Dependency checksum file.
└── README.md            # Project documentation.
