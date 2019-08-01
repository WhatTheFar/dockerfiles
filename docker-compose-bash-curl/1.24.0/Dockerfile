# docker run --rm \
#     -v /var/run/docker.sock:/var/run/docker.sock \
#     -v "$PWD:/$PWD" \
#     -w="/$PWD" \
#     -it --entrypoint "/bin/bash" \
#     whatthefar/docker-compose-bash-curl:1.24.0

FROM docker/compose:1.24.0

RUN apk update && \
    apk upgrade && \
    apk add bash && \
    apk add curl