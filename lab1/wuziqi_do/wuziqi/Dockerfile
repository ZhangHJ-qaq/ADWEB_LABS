FROM node:16
RUN mkdir -p /huajuan/wuziqi
COPY "./content.tar.gz" "/huajuan/wuziqi"
WORKDIR /huajuan/wuziqi
RUN  tar -zxvf ./content.tar.gz
WORKDIR /huajuan/wuziqi/content
RUN npm install websocket && npm install ws && npm install forever
CMD ["node" ,"/huajuan/wuziqi/content/ChessServer.js" ]