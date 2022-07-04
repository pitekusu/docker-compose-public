FROM python:3.9.7-slim-buster

RUN pip install --upgrade pip
RUN pip install flask==2.0.3
#RUN pip install jinja2

ENV PORT 80

WORKDIR /app

COPY app /app

CMD ["python", "app.py"]