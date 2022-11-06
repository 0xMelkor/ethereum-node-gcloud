# Geth + Lighthouse kubernetes deployment on GKE
A Kubernetes project to deploy a PoS Ethereum full node on Google GKE using Geth "execution layer" and Lighthouse "consensus layer".


![Cluster architecture](./docs/images/arch.png)

# InfluxDB 
```
CREATE USER "user" WITH PASSWORD 'password'
CREATE DATABASE "geth"
GRANT ALL ON "geth" TO "user"
```
