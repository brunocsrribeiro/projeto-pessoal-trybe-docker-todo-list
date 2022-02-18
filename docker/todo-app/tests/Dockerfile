FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests/
ADD node_modules.tar.gz ./
COPY . /todo-app/tests/
EXPOSE 3000
CMD [ "npm", "start" ]

