FROM python:3.7.3-alpine3.9

COPY requirements.txt /
RUN pip install -r requirements.txt

COPY seed.py /
CMD python3 seed.py