# Fakir MonoRepo for Webapps

This repository is our basic boilerplate to start new webapplications in the following modern webstack:

* node/nestjs backend
* fullstack typescript
* react (vite)
* nx
* docker/kubernetes deployment


# Addtional recommendations

We use vscode with this stack.

## how to add a new nestjs microservice?


    nx g @nrwl/nest:app microserviceName

## how to add a new reactjs project

    nx g @nrwl/react:app


# Todo

[] nestjs
[] react build
[] production setup
[] docker container


# files info

* workspace.json -> for  nx
* .vscode -> settings for vscode
* apps folder -> contains one folder per project
