FROM djschaper/shellcheck-bats-alpine3.7:stable

WORKDIR /ssl

RUN apk --no-cache --virtual .run-depends add \
    bash \
    curl \
    drill \
    git \
    openssh \
    openssl

ENTRYPOINT ["/bin/sh"]
