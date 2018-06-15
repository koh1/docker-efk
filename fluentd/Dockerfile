# fluentd/Dockerfile
FROM fluent/fluentd:v0.12-debian
RUN apt-get update && apt-get install -y dstat
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "1.16.1"]
RUN ["gem", "install", "fluent-plugin-dstat", "--no-rdoc", "--no-ri", "--version", "0.3.3"]
