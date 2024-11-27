FROM python:3.7-slim

WORKDIR /opt2
ADD . /opt2
RUN pip install -r requirements.txt
EXPOSE 80
CMD ["python","app.py"]
