FROM node:6.11.1

ENV HOME=/home/app

COPY package.json package-lock.json /home/app/docker_money/

WORKDIR /home/app/docker_money

RUN npm install --silent --progress=false

COPY . /home/app/docker_money

CMD ["npm", "dev"]
