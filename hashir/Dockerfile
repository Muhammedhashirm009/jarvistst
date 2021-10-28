FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Muhammedhashirm009/jarvistst /root/Hashirbot

WORKDIR /root/Hashirbot

ENV TZ=Europe/Istanbul

RUN npm install supervisor -g

RUN apt-get install libwebp

RUN apt-get install mc

RUN apt-get install ffmpeg

RUN apt-get install wget

RUN apt-get install tesseract

RUN apt-get install cowsay -y

RUN apt-get install sox -y

RUN apt-get install jq -y

RUN apt-get install figlet -y

RUN apt-get install nmap

RUN yarn install --no-audit

RUN wget -O ~/../usr/share/tessdata/ind.traineddata "https://github.com/tesseract-ocr/tessdata/blob/master/ind.traineddata?raw=true"

CMD ["node", "main.js"]




