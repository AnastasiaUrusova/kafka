FROM python:3.9-slim

WORKDIR /app

COPY . .

RUN pip install kafka-python

CMD ["python", "notification_service.py"]