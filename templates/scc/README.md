# SAP Cloud Connector Template

This is a template to build a SAP Cloud Connector Docker image from the original SAP sources: https://tools.eu1.hana.ondemand.com/#cloud.

See this [repository](https://github.com/nzamani/sap-cloud-connector-docker) from Nabi Zamani and his [Blog](https://community.sap.com/t5/technology-blogs-by-members/installing-sap-cloud-connector-into-docker-and-connecting-it-to-sap-cloud/ba-p/13376377) for further information.


# Build an image

Modify the Dockerfile and change the following ARGS to your needs:

```
ARG SAPCC_VERSION=2.18.0
ARG SAPJVM_VERSION=8.1.103
```

Rund the build process:

```bash
docker build -t sapcc .
```

# Start with docker compose

## Start

```
docker compose up
```

Login via: https://localhost:8443/

## First Login

At the first login the user 'Administrator' with password 'manage' is used. 
Change the password and configure your SAP Cloud Connector instance.

Further information can be found here: https://help.sap.com/docs/connectivity/sap-btp-connectivity-cf/cloud-connector-initial-configuration 

## Stop

Stop with CTRL-C or 'docker compose down'.


