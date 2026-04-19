# CS-GY 6903

Applied Cryptography with Z Chen at NYU

## Project 5 - PKI-TLS (individual)

- Matthew Bentz (mb9661@nyu.edu)

## Project Outline

[TLS_PKI Project -v4.pdf](TLS_PKI%20Project%20-v4.pdf)

## Usage

```
docker compose up -d

# setup server with easy-rsa
docker exec -it server sh
apk update && apk add --no-cache openssl easy-rsa

# setup client with curl and tcpdump
docker exec -it client bash
apt-get update && apt-get install -y curl tcpdump
```

Continue on to run experiments :smiley:.