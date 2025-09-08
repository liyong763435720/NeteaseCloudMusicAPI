FROM node:18-alpine

WORKDIR /app

COPY build/NeteaseCloudMusicApiBackup /app

RUN npm install

COPY run.sh /run.sh
RUN chmod +x /run.sh

EXPOSE 3000


CMD [ "/run.sh" ]
