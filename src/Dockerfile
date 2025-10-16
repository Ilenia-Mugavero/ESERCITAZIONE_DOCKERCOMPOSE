
FROM python:3.10-alpine

COPY . /app/

# Imposta la cartella di lavoro
WORKDIR /app

# Installa le dipendenze
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

CMD ["python", "app.py"]