# Monitoring Application

A Linux monitoring platform for collecting, storing, and visualizing system performance metrics.

## Components

- **Collector:** C application for gathering Linux system metrics, including CPU, memory, disk, and network usage.
- **Backend:** C-based HTTP REST API for receiving, storing, and querying metrics.
- **Database:** PostgreSQL for storing server information and historical performance metrics.
- **Dashboard:** HTML, CSS, and JavaScript frontend for displaying server status, metrics, and performance graphs.

## Project Structure

```text
.
├── backend/       # C REST API
├── collector/     # C metrics collector
├── dashboard/     # HTML, CSS, JavaScript frontend
├── database/      # PostgreSQL schema and migrations
├── docs/          # Project documentation
└── README.md
```

## Development Status

Currently in development.
