FROM node:16-alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"] 
    # same as before just start instead of dev
    # make sure package.json has a start script