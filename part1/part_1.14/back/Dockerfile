FROM golang:1.16

ENV PORT=8080
ENV REQUEST_ORIGIN=http://localhost:5000

EXPOSE ${PORT}

WORKDIR /usr/src/app

COPY . .

RUN go build

CMD ./server

#docker build . -t backend-project
#docker run -p 8080:8080 backend-project