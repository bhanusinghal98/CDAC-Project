FROM node:14.15.0
RUN mkdir /usr/src/app

RUN npm install -g @angular/cli@11.0.9

COPY . /user/src/app

CMD ng serve --host 0.0.0.0 --port 4200