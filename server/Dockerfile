# Set the base image.
FROM python:latest

# Create and cd into the /app directory.
WORKDIR /app

COPY ./requirements.txt /app
RUN pip install --no-cache-dir --upgrade -r requirements.txt

COPY . /app

CMD []
