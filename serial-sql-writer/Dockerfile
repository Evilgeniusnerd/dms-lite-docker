FROM python:3.11.0a5-buster

COPY serial_sqlwriter.py /

RUN pip install pyserial

ENTRYPOINT [ "python3", "serial_sqlwriter.py" ]