From node:alpine

WORKDIR app/simpleweb

ADD ./package.json ./

RUN npm install

COPY ./ ./ 

EXPOSE 3000

CMD ["npm","start"]


# docker build -t sunil28/simpleweb .
# docker run -it -p 3000:3000 sunil28/simpleweb
# docker exec -it <container id> sh