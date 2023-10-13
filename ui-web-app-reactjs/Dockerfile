# the base image
FROM node:8

WORKDIR /app
COPY . .

RUN npm install

EXPOSE 8080

# Runs in development Mode
CMD ["npm", "start"]