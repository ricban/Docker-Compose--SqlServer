# Using Docker to run Microsoft SQL Server 2022
A guide for quickly setting up Microsoft SQL Server 2022 in a docker container. It uses docker compose to easily manage container configurations.

## Requirement

* Docker Desktop version 4.x

## Usage

1. Clone this repository and navigate to it
2. Create _`sapassword.env`_ file and set the **`sa`** password

```
MSSQL_SA_PASSWORD=YOUR SA PASSWORD
```
3. Excute the **`Start`** command

## Commands

**Start**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _`docker compose up -d ↩`_

**Stop**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _`docker compose down ↩`_

## SQL Server Management Studio (SSMS) Connection Details

![alt text](https://github.com/ricban/Docker-Compose--SqlServer/blob/main/ssms.jpg)
