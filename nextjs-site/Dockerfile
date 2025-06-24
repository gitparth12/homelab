FROM node:24.1.0

WORKDIR /app
COPY site/ /app/

RUN pwd
RUN ls
RUN npm install && npm run build

EXPOSE 3000
CMD ["npm", "start"]

