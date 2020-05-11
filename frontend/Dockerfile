FROM node:13.2.0

# set work directory
WORKDIR /app

# copy project
COPY . /app/

# install dependencies
RUN npm install -g npm@latest --registry=https://registry.npm.taobao.org
RUN npm install --registry=https://registry.npm.taobao.org


# build project
RUN npm run build
