# Create file under /tmp to ensure files inside '/tmp' are not overridden.
FROM alpine:3.18.5
RUN mkdir -p /tmp/foo \
  && echo 123 > /tmp/foo/file.txt
