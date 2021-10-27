FROM python:3.9
COPY / ./app/
WORKDIR app
RUN /bin/sh -c 'pip install --no-cache-dir --index-url
https://nexus.dev.afsmtddso.com/repository/https://github.com/lcarpent001/devops-camp-pipeline.git/simple -r requirements.txt'
ENTRYPOINT ["python"]
CMD ["server.py"
