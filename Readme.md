# golang project with docker

Normal docker build (not using modules) - image size is 775MB

`docker build . -t go-sample-app-full`

Optimized Build (with modules - image size is 389MB

`docker build . -f Dockerfile.mod -t go-sample-app-modules`

Multi-stage build (fully optimized) - image size is 16 MB

`docker build . -f Dockerfile.multistage -t go-sample-app-multi`


