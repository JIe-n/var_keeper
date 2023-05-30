FROM python:3.12-rc-alpine3.18
WORKDIR /app
COPY requirements.txt /app
COPY /src/app /app
RUN pip install -r requirements.txt
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]
