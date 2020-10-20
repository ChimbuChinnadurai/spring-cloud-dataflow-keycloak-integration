# spring-cloud-dataflow-keycloak-integration

This repo contains sample server and skipper config files used to integrate it with dataflow

This repo only shows the required config to enable the keycloak integration , For other configurations please refer the official documents

The details are not currently documented in the spring cloud dataflow documents and any config you have for version <= 2.2.0 will not work from version 2.3.0

For version <=2.2.0 you can directly define the required scope under client scopes in keycloak and no need add scope values in dataflow config.It will do the mapping automatically based on the scope included in the authorisation token.

For version >=2.3.0 you need to define the scope in keycloak and also in the data flow server & skipper configuration to get this work correctly

Keycloak configurations - Yet to be added in this repo