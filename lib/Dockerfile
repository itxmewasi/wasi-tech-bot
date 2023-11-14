FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/itxmewasi/wasi-tech-bot /root/itxmewasi
WORKDIR /root/itxmewasi 
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
