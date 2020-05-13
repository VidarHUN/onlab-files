FROM envoyproxy/envoy:v1.14.1
COPY envoy.yaml /etc/envoy/envoy.yml
RUN apt-get update && apt-get install -y tcpdump && apt-get install -y net-tools
