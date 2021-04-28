FROM node:14.14.0-alpine
WORKDIR '/app/'
COPY ./package.json ./
RUN npm install
COPY . .
# Only need to change the startup command
# This command is defined in package.json
CMD ["npm", "run", "start"] 