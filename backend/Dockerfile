FROM node:alpine
WORKDIR "/app"
COPY ./backend/package.json ./
RUN npm install
COPY . .
CMD ["npm" , "run", "start"]