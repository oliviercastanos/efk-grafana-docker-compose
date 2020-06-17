FROM fluent/fluentd:v0.12-debian
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "1.9.2"]
COPY fluent.conf /fluentd/etc/fluent.conf
RUN chown fluent:fluent /fluentd/etc/fluent.conf
RUN chmod  775 /fluentd/etc/fluent.conf
