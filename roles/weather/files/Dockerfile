#########
# Dockerfile to build my weather app
# Based on python

FROM python:3
ADD script.py /
#WORKDIR /usr/src/app

#COPY requirements.txt ./
RUN pip install  pyowm

COPY . .
CMD echo "test"
CMD [ "python", "./script.py" ]