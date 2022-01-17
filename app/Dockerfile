FROM python:3.9-slim

EXPOSE 8000

COPY requirements.txt .
RUN pip install --upgrade pip
RUN pip install -r requirements.txt

WORKDIR /app

CMD ["python", "main.py"]