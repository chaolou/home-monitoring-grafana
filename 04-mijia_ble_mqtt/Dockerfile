FROM python:3.7-alpine

LABEL maintainer="Nilhcem" \
      description="Sensor Data to MQTT"

COPY requirements.txt /
RUN pip install -r /requirements.txt

COPY . /app
WORKDIR /app

CMD ["python3", "-u", "main.py"]
