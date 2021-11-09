# Micro Rockets 🚀

Micro rocket is a small example implementation of a microservice application. It's a game, where you launch rockets into space and hope that space junk doesn't hit them!

## Running locally

To get up and running, simply clone this repo locally and docker compose up and head over to <http://localhost/>.

## Tracing

To help work out what is happening in the live system, there is a distributed tracing service available at <http://localhost:16686/>.
## Services

There are 4 services that make up the application:
| | |
|-|-|
| User Manager | [![User Manager](https://github.com/tharsus-ltd/ur-user-manager/actions/workflows/docker-image.yml/badge.svg)](https://github.com/tharsus-ltd/ur-user-manager) |
| Rocket Manager | [![User Manager](https://github.com/tharsus-ltd/ur-rocket-manager/actions/workflows/docker-image.yml/badge.svg)](https://github.com/tharsus-ltd/ur-rocket-manager) |
| Frontend UI | [![User Manager](https://github.com/tharsus-ltd/ur-frontend/actions/workflows/docker-image.yml/badge.svg)](https://github.com/tharsus-ltd/ur-frontend) |
| Junk Manager | [![User Manager](https://github.com/tharsus-ltd/ur-junk-manager/actions/workflows/docker-image.yml/badge.svg)](https://github.com/tharsus-ltd/ur-junk-manager) |
