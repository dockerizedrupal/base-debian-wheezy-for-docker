# docker-base-debian-wheezy

## Build the image

    TMP="$(mktemp -d)" \
      && git clone https://github.com/dockerizedrupal/docker-base-debian-wheezy.git "${TMP}" \
      && cd "${TMP}" \
      && sudo docker build -t dockerizedrupal/base-debian-wheezy:latest . \
      && cd -

## License

**MIT**
