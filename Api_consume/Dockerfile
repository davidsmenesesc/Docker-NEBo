FROM python:3.9-slim-buster
WORKDIR /api_consume
COPY . /api_consume
RUN pip install -r requirements.txt
EXPOSE 4000
CMD python ./main.py 