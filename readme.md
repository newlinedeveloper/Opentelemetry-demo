## Opentelemetry Observability for Node js application

#### zipkin installation

```
docker run -d -p 9411:9411 --name zipkin openzipkin/zipkin

http://localhost:9411

```


#### Node js project setup

```
npm init -y

```

#### Packages installation

```
npm i @opentelemetry/core @opentelemetry/node @opentelemetry/plugin-http @opentelemetry/pluging-https @opentelemetry/exporter-zipkin @opentelemetry/tracing express @opentelemetry/plugin-express

```
