Quickstart setup for Supply Chain Orchestrator Community Edition

## Prerequisites
- docker

## Contents

1. docker-compose.yml

This docker compose file pulls and runs two containers: the SCO community edition and the IRIS webgateway.

2. webgateway files

Running the wegateway requires some additional configuration files. More options/examples are available [here](https://github.com/intersystems-community/webgateway-examples), but you can get started with the simple setup included here.

## Getting started

To pull and run the containers, just run ```docker compose up -d```.

The SMP will then be available here: http://localhost:52773/csp/sys/%25CSP.Portal.Home.zen?$NAMESPACE=SC

**Not sure what to build first?**
 Checkout the [SCO Workbench](https://github.com/intersystems-community/sco-workbench), an open-source UI application with a built in AI agent designed to help users get started with Supply Chain Orchestrator.