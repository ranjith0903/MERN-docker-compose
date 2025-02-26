FROM node:18.9.1//node image

WORKDIR /app //specifying the directory in which all the dependencies and library should be installed in docker container

COPY package.json . //copying the package.json into the /app because it contains info about all the dependencies which should be installed

RUN npm install // to install dependenies 

COPY . . // copy the entire backend code into app

EXPOSE 5050 //expose  the port so that we can bind with the host port

CMD ["npm", "start"] // commands to start the backend

