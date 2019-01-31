FROM python:3.4-alpine
ADD . /usr
WORKDIR /usr
RUN pip install -r requirements.txt
CMD ["python", "app.py"]