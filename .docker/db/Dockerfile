# Derived from official mysql image (our base image)
FROM mysql:5.7

# Add the content of the sql-scripts/ directory to your image
# All scripts in docker-entrypoint-initdb.d/ are automatically
# executed during container startup
COPY init/ /docker-entrypoint-initdb.d/