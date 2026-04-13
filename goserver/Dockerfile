FROM debian:stable-slim

# COPY source destination
# replaced goserver with docker here since that is the name of the repo
COPY server /bin/goserver

ENV PORT=8991

CMD ["/bin/goserver"]