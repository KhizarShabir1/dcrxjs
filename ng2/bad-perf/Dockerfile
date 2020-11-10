

FROM node:12.18.4
LABEL maintainer="educative@educative.io"

WORKDIR /app
COPY package.json /app
COPY . /app

RUN npm cache verify

RUN npm install 
#RUN npm install -y express




#EXPOSE 8080
#CMD ["cd","creatingObservables/"]


CMD ["npm","run", "start"]




