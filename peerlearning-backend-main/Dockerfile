FROM node

WORKDIR /dockerImage

COPY . .

RUN npm install

EXPOSE 8000

CMD ["npm" ,"run", "dev"]