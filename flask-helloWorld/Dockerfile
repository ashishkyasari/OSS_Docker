
FROM python:3.8-alpine
RUN pip install Flask

WORKDIR /app

COPY ./app.py  ./app.py
COPY ./templates  ./templates

ENTRYPOINT [ "python" ]
CMD ["app.py" ]