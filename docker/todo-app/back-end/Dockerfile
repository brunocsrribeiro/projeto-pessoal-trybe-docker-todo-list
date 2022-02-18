FROM node:14-alpine
WORKDIR /todo-app/back-end/
ADD node_modules.tar.gz ./
COPY . /todo-app/back-end/
EXPOSE 3001
CMD [ "npm", "start" ]
