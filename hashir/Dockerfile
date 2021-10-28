

FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Muhammedhashirm009/jarvistst /root/Hashirbot

WORKDIR /root/Hashirbot

ENV TZ=Europe/Istanbul

RUN npm install supervisor -g

RUN heroku-apt install libwebp

RUN heroku-apt install mc

RUN heroku-apt install ffmpeg

RUN heroku-apt install wget

RUN heroku-apt install tesseract

RUN heroku-apt install cowsay -y

RUN heroku-apt install sox -y

RUN heroku-apt install jq -y

RUN heroku-apt install figlet -y

RUN heroku-apt install nmap

RUN yarn install --no-audit

RUN wget -O ~/../usr/share/tessdata/ind.traineddata "https://github.com/tesseract-ocr/tessdata/blob/master/ind.traineddata?raw=true"

CMD ["node", "main.js"]
