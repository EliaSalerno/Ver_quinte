FROM imgver
RUN apk update
RUN python3 -m ensurepip
RUN python3 -m pip install flask
RUN python3 -m pip install requests
COPY prova.py .
CMD python3 -m flask --app prova.py run --host 0.0.0.0
