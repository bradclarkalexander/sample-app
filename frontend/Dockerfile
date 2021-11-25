FROM python:3.8

COPY ./requirments.txt /webapp/requirments.txt

WORKDIR /webapp

RUN pip install -r requirments.txt

COPY webapp/* /webapp

ENTRYPOINT [ "python" ]

CMD [ "app.py" ]
