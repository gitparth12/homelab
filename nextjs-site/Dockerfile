FROM node:18-alpine

WORKDIR /app
COPY site/ .                      # ← copy submodule contents

RUN npm install && npm run build

EXPOSE 3000
CMD ["npm", "start"]

