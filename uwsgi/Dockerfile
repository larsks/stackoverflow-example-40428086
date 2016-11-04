FROM alpine
RUN apk add --update uwsgi uwsgi-python py-flask
COPY uwsgi.conf /uwsgi.conf
COPY server.py /server.py
CMD ["uwsgi", "--ini", "uwsgi.conf"]
