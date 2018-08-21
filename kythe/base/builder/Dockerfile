FROM gcr.io/jonjohnson-test/kythe/indexer
COPY . /go/src/${PACKAGE}
WORKDIR /go/src/${PACKAGE}
RUN bash /index.sh ./...
