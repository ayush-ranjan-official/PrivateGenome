FROM python:3.11-slim
WORKDIR /app
COPY requirements.txt ./
RUN pip install -r requirements.txt
COPY . .
ENTRYPOINT ["python3", "/app/src/app.py"]