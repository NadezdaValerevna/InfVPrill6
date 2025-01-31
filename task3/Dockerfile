FROM python:3.9-slim

WORKDIR /app

COPY requirements.txt requirements.txt
COPY app.py .

RUN pip install -r requirements.txt

EXPOSE 8088

CMD ["python", "app.py"]