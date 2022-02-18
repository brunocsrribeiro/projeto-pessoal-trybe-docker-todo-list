FROM node:14-alpine
WORKDIR /todo-app/front-end/
ADD node_modules.tar.gz ./
COPY . /todo-app/front-end/
EXPOSE 3000
CMD [ "npm", "start" ]
