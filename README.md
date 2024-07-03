# devcontainer-node-typescript

vscode open in devcontainer

CRT + P OR F1: `>Dev containers: reopen in devcontainer`

## `.devcontainer/devcontainer.json`

This is a configuration file for a development container in Visual Studio Code. It specifies the name of the container, the path to the Dockerfile, and various settings and extensions that will be used when the container is created.

The name field specifies the name of the container.

The dockerFile field specifies the path to the Dockerfile that will be used to build the container.

The settings field sets default values for the container's settings.json file. In this case, it sets the terminal shell to /bin/bash.

The extensions field specifies a list of extensions that will be installed in the container when it is created.

The forwardPorts field specifies a list of ports that will be forwarded from the container to the local machine.

The commented out postCreateCommand field would allow you to run commands after the container is created.

The commented out remoteUser field would allow you to connect to the container as a non-root user.

## `.devcontainer/Dockerfile`

This Dockerfile snippet is referencing a base image for a development container with TypeScript and Node.js. It installs dependencies using npm and comments out the installation of the TypeScript globally.

## Info

node version

```sh
node --version
```

typescritp version

```sh
tsc -v
```

install angular 16

```sh
npm i @angular/cli@16
```
