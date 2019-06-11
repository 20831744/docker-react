# specify a base image
From node:alpine

#Install some dependancies

workdir /usr/app
copy ./package.json  ./
RUN npm install
copy ./ ./
#Defaulr command

CMD ["npm","start"]

