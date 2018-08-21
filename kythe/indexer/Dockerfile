# In knative
FROM gcr.io/jonjohnson-test/kythe/bins as bins

# Index the code, producing the serving_table
FROM golang as indexer
COPY --from=bins /out/gotool /gotool
COPY --from=bins /out/go_indexer /go_indexer
COPY --from=bins /out/write_tables /write_tables
COPY index.sh /index.sh
