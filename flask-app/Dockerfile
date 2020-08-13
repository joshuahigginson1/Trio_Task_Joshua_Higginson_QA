#Use Python Image

FROM python:3-alpine

# Install apt package manager dependencies

RUN sudo apt-get update
 
# Copy contents into image.

COPY . .
 
# run our pip dependencies.

RUN pip3 install flask SQLalchemy

# Expose correct port.

EXPOSE 5000

# Create an entrypoint.

ENTRYPOINT ["python3", "app.py"]
