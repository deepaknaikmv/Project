FROM node:current-slim
WORKDIR /src/app
COPY package.json /src/app
COPY package.json /src/db/conn
COPY package.json /src/models/registers
COPY . /app
COPY . /src/db/conn
COPY . /src/models/registers
RUN npm install
EXPOSE 3001
CMD ["node","dev"]