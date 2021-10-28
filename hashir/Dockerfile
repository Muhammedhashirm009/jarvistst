FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Muhammedhashirm009/jarvistst /root/Hashirbot

WORKDIR /root/Hashirbot

ENV TZ=Europe/Istanbul

RUN npm install supervisor -g

RUN apt install libwebp

RUN apt install mc

RUN apt install ffmpeg

RUN apt install wget

RUN apt install tesseract

RUN apt install cowsay -y

RUN apt install sox -y

RUN apt install jq -y

RUN apt install figlet -y

RUN apt install nmap

RUN yarn install --no-audit

RUN wget -O ~/../usr/share/tessdata/ind.traineddata "https://github.com/tesseract-ocr/tessdata/blob/master/ind.traineddata?raw=true"

CMD ["node", "main.js"]


