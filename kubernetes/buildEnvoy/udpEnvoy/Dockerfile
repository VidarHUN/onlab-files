FROM envoyproxy/envoy:v1.14.1
COPY envoy_upd.yaml /etc/envoy/envoy.yaml
RUN apt-get update && apt-get install -y tcpdump && apt-get install -y net-tools
