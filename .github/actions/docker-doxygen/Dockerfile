FROM python:3.7-alpine

# Install dependencies. 
RUN apk add doxygen graphviz ttf-freefont git rsync

USER 1001

# Run update.py script.
CMD ["python", "update.py" ]
