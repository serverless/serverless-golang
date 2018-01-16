# Serverless Template for Golang

This repository contains template for creating serverless services written in Golang.

## Quick Start

1. Create a new service based on this template

```
serverless create -u https://github.com/serverless/serverless-golang/ -p myservice
```

2. Compile function

```
cd myservice
GOOS=linux go build -o bin/main
```

3. Deploy!

```
serverless deploy
```
