FROM alpine 
RUN apk update && apk add iputils-ping && apk add nano && apk add python3 && apk add bash
COPY prova.py .
CMD python3 prova.py
