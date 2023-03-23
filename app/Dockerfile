FROM python:3.10

WORKDIR /app
COPY requirementes.txt /app/app/requirements.txt

RUN pip install --no-cache-dir --upgrade -r app/requirements.txt
COPY . /app/requirements.txt

CMD bash -c "while true; do sleep 1; done"