ARG PYTHON_VERSION=3.12
FROM python:${PYTHON_VERSION}-slim

WORKDIR /app

COPY app ./app

EXPOSE 8000

CMD ["python", "app/app.py"]
