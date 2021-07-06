FROM python:alpine 

RUN pip install flask

COPY server.py /srv/

EXPOSE 8081

ENTRYPOINT ["python", "/srv/server.py"]

