FROM docker.io/fluent/fluentd:v1.15.3-debian-amd64-1.2
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.2.4"]
USER fluent
