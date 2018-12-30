FROM wordpress
WORKDIR /app
ADD . /app
RUN apt-get update && apt-get install -y --force-yes nfs-common
EXPOSE 3000
