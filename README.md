# wiremock-sandbox

Setup wiremock mapping and a catch all proxy for the rest. Run in docker with following command
```
docker run -it --rm -p 8080:8080 --name wiremock -v $PWD:/home/wiremock wiremock/wiremock:2.33.2
```
On Windows 10 run following
```
docker run -it --rm -p 8080:8080 --name wiremock -v ${PWD}:/home/wiremock wiremock/wiremock:2.33.2
```