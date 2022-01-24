FROM rabbitmq:3.8-management-alpine

RUN set -eux; \
  cd "$RABBITMQ_HOME/plugins"; \
  wget "https://github.com/rabbitmq/rabbitmq-message-timestamp/releases/download/v3.8.0/rabbitmq_message_timestamp-3.8.0.ez"; \
  chown rabbitmq:rabbitmq rabbitmq_message_timestamp-3.8.0.ez
