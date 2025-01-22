FROM python:3.9

RUN apt-get install wget
RUN pip install pandas sqlalchemy requests psycopg2

WORKDIR /app
COPY ingest-yellow.py ingest-yellow.py

ENTRYPOINT [ "python", "ingest-yellow.py" ]