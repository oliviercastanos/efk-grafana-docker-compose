FROM fluent/fluentd:v0.12
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "1.9.5"]
COPY fluent.conf /fluentd/etc/fluent.conf
RUN chown fluent:fluent /fluentd/etc/fluent.conf
RUN chmod  775 /fluentd/etc/fluent.conf
