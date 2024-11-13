FROM python:3.12-slim
WORKDIR /app
RUN pip install "fastapi[standard]" httpx pydantic-settings
COPY rpc_gateway.py /app/main.py

