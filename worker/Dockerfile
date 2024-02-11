FROM node:alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
COPY . .

# in prod docker we changed dev to start, and you will find in package.json in scripts section we have both, dev and start
CMD ["npm", "run", "start"]  