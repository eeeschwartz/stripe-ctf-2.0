# This image is a pain because you have to rebuild the container on each code change
FROM python:2-onbuild
RUN pip install flask flup
ADD . /app
