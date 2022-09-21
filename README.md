# Docker-Compose--SqlServer
Creates a Microsoft SQL Server container using docker compose

## Requirement

* Docker Desktop version 4.12.0 (85629)

## Usage

1. Clone this repository and navigate to it
2. Configure the **`sa`** password in `sapassword.env` file
````
MSSQL_SA_PASSWORD=<YOUR SA PASSWORD>
````
3. Excute the start command

## Commands

* To start `docker compose up -d ↩`

* To Stop  `docker compose down ↩`

## Connect via SSMS

![alt text](https://github.com/ricban/Docker-Compose--SqlServer/blob/main/ssms.jpg)
