# Derived from official mysql image (our base image)

FROM mysql:5.7

# Add the content of the .sql file to your image

COPY . .

# All scripts in docker-entrypoint-initdb.d/ are automatically
# executed during container startup

COPY ./db /docker-entrypoint-initdb.d/

