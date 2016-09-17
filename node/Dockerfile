FROM node:6.6.0-wheezy

RUN mkdir /usr/src/app
RUN git clone https://github.com/radiscope/radiscope-web.git /usr/src/app/
WORKDIR /usr/src/app/
RUN npm install
EXPOSE 4000

CMD ["npm", "start"]

