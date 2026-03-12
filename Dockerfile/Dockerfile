FROM python:3.13-slim

WORKDIR /app

COPY . .

RUN pip install --no-cache-dir -r requiremnts.txt

EXPOSE 80

CMD ["python","app.py"]