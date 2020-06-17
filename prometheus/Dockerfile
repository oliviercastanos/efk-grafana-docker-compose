FROM prom/prometheus:v2.14.0
COPY prometheus.yml /etc/prometheus/prometheus.yml
USER root
RUN chown 65534:65534  /etc/prometheus/prometheus.yml
USER 65534