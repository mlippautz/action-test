FROM python:3.7-alpine

# Copy entrypoint and update file.
COPY update.py /update.py

# Deps.
RUN apk add doxygen graphviz ttf-freefont

# Start executing at entrypoint.
CMD ["python", "/update.py"]

