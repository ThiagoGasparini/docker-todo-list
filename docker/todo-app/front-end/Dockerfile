FROM node:14-alpine AS todofrontend
EXPOSE 3000
WORKDIR /
ADD node_modules.tar.gz .
COPY . .
RUN npm install
CMD [ "npm", "start" ]
