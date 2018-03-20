FROM python:3.4
ADD . /docker      
WORKDIR /src
RUN pip install -r /docker/requirements.txt
CMD ["python", "app.py"]
