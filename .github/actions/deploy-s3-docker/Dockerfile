FROM python:latest

COPY requirements.txt /requirements.txt

RUN pip install --upgrade pip

RUN pip install -r requirements.txt

COPY deployment.py /deployment.py

CMD ["python", "/deployment.py"]