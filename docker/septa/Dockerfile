
FROM python:3

COPY requirements.txt /
RUN pip3 install -r /requirements.txt

COPY get-train-data.py /
COPY entrypoint.sh /


ENTRYPOINT [ "/entrypoint.sh" ]

