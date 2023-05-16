FROM provaimmagineh
RUN apk update && apk add iputils && apk add python3
RUN python3 -m ensurepip
RUN python3 -m pip install flask
COPY prova.py .
CMD python3 -m flask --app prova.py run --host 0.0.0.0