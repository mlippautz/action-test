FROM python:3.7-alpine

#COPY ../../../update.py /update.py
#COPY ../../../Doxyfile /Doxyfile

# Deps.
RUN apk add doxygen graphviz ttf-freefont git rsync

# Start executing at entrypoint.
#CMD ["python", "$GITHUB_WORKSPACE/update.py" ]
ENTRYPOINT ["ls -al"]



