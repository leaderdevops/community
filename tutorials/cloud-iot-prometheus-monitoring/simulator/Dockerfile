FROM alpine:3.17
RUN apk add --no-cache ca-certificates
ADD simulator /simulator
ADD US-cities.csv /US-cities.csv
ENTRYPOINT ["/simulator"]
