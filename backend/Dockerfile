FROM node:6.11.1

ENV HOME=/home/app

COPY package.json package-lock.json /home/app/docker_money/

WORKDIR $HOME/docker_money

RUN npm install --progress=false

COPY . $HOME/docker_money

CMD [ "npm", "run", "dev" ]
