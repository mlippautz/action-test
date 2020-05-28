# Alpine Linux container.
FROM alpine:edge

# Copy entrypoint and update file.
COPY entrypoint.sh /entrypoint.sh

# Deps.
RUN apk add doxygen graphviz ttf-freefont

# Start executing at entrypoint.
ENTRYPOINT ["/entrypoint.sh"]

