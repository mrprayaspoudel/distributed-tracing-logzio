docker pull logzio/otel-collector-traces

docker run -e LOGZIO_REGION=us -e LOGZIO_TRACES_TOKEN=<token> -p 55678-55680:55678-55680 -p 1777:1777 -p 9411:9411 -p 9943:9943 -p 6831:6831 -p 6832:6832 -p 14250:14250 -p 14268:14268 -p 4317:4317 -p 4318:4318 -p 55681:55681 logzio/otel-collector-traces
