FROM python

COPY ./app/ /app

WORKDIR /app

run pip install -r requirements.txt

EXPOSE 8000

ENTRYPOINT [ "python3" ]

HEALTHCHECK --interval=5s --timeout=3s CMD curl -f http://0.0.0.0:8000

CMD [ "manage.py", "runserver", "0.0.0.0:8000" ]