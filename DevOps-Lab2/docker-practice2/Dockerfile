FROM ubuntu:20.04

RUN apt-get update && apt-get install -y python3 && rm -rf /var/lib/apt/lists/*

COPY app.py /app/app.py

CMD ["python3", "/app/app.py"]
