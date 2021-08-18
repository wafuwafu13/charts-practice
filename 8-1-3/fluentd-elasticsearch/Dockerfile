FROM fluent/fluentd:v1.13-1

USER root
RUN gem install fluent-plugin-elasticsearch --version 1.9.2
COPY fluent.conf /fluentd/etc/fluent.conf
