FROM node:16
RUN mkdir -p /huajuan/wuziqi
WORKDIR /huajuan/wuziqi
COPY "./ChessServer.js" "/huajuan/wuziqi"
RUN npm install websocket && npm install ws
CMD ["node" ,"/huajuan/wuziqi/ChessServer.js" ]