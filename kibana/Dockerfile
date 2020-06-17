FROM docker.elastic.co/kibana/kibana:7.4.2
USER root
ADD kibana.yml /usr/share/kibana/config/kibana.yml
RUN chown kibana:root /usr/share/kibana/config/kibana.yml
USER kibana