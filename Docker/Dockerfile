from gocorona

WORKDIR /app
ADD . .

CMD gunicorn app:app --bind 0.0.0.0:$PORT --reload


