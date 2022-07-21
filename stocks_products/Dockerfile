FROM python:3.9-alpine

COPY . /src

WORKDIR src

RUN pip3 install --no-cache-dir --upgrade -r /src/requirements.txt

EXPOSE 8000

CMD ["python3", "manage.py", "runserver", "0.0.0.0:8000"]