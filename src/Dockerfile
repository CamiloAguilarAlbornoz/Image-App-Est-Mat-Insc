FROM node:18-alpine3.15
RUN mkdir imageApp
WORKDIR /imageApp
RUN npm init -y
RUN npm i axios cors express multer
RUN mkdir /src
WORKDIR /imageApp/src
COPY /index.js .
EXPOSE 3000
CMD node index.js