FROM python:3.9
COPY / ./app/
WORKDIR app
RUN /bin/sh -c 'pip install --no-cache-dir --index-url
https://nexus.dev.afsmtddso.com/repository/<nexus-repo-name>/simple -r requirements.txt'
ENTRYPOINT ["python"]
CMD ["server.py"