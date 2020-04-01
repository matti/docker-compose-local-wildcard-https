# docker-compose-local-wildcard-https

## How

put `*.yourdomain.tld.crt` in `ssl/certs`
and `*.yourdomain.tld.crt` in `ssl/private`

    docker-compose up

then open:

    - https://doom.yourdomain.tld
    - https://anothername.yourdomain.tld
