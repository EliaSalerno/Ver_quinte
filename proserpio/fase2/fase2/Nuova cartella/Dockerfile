FROM imgfase2a
RUN apk update && apk add gcc && apk add python3 && apk add curl
RUN python3 -m ensurepip
RUN python3 -m pip install flask
COPY prova.py .
CMD python3 -m flask --app prova.py run --host 0.0.0.0

