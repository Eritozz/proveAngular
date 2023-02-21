FROM node:latest
RUN apt-get -y update 
RUN npm i -g @angular/cli
EXPOSE 4200
ENTRYPOINT cd/app/hello-world && npm install && ng serve --host 0.0.0.0
