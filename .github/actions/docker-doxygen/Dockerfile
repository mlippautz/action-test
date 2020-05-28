FROM python:3

# Copy entrypoint and update file.
COPY update.py /update.py

# Deps.
RUN apk add doxygen graphviz ttf-freefont python3

# Start executing at entrypoint.
CMD ["python", "./update.py"]

