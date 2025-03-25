<div align="center">
  <h1>Stonks Portfolio Go Microservice</h1>
</div>

<p align="center">
  <img alt="Go" src="https://img.shields.io/badge/Go-black?style=for-the-badge&logo=go&logoColor=blue"/>

  <img alt="Kafka" src="https://img.shields.io/badge/kafka-black.svg?style=for-the-badge"/>

  <img alt="Docker" src="https://img.shields.io/badge/docker-black?style=for-the-badge&logo=docker&logoColor=blue"/>
</p>

# About 🔎

Assets trade application where is possible to create buy and sell orders.

# How to run 🏃

## Prerequisites
- Docker

This is only a microservice of a whole project, you will need the other parts to run it properly:
- [NextJs Frontend](https://github.com/m1guelsb/stonks-frontend)
- [NestJs Backend](https://github.com/m1guelsb/stonks-backend)

## Installation

1. Clone the repo
   ```sh
   git clone https://github.com/m1guelsb/stonks-b3
   ```
3. Start docker containers
   ```sh
   docker compose up
   ```
4. Start go application
   ```sh
   go run cmd/trade/main.go
   ```

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Miguel Barbosa - [@m1guelsb](https://www.linkedin.com/in/m1guelsb)
