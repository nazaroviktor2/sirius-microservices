FROM python:3.12-slim
WORKDIR /app
RUN pip install "fastapi[standard]" httpx pydantic-settings prometheus_client
COPY main.py /app
