# Alpine Linux container.
FROM alpine:edge

# Copy entrypoint and update file.
COPY entrypoint.sh /entrypoint.sh
COPY update.py /update.py

# Deps.
RUN apk add doxygen graphviz ttf-freefont python3

# Start executing at entrypoint.
ENTRYPOINT ["/entrypoint.sh"]

