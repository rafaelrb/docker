FROM node:4.6
WORKDIR /app
ADD . /app
RUN npm install
RUN apt-get update && apt-get install -y --force-yes nfs-common
EXPOSE 3000
CMD npm start
