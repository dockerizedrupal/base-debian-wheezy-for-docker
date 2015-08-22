# docker-base

## Build the image

    TMP="$(mktemp -d)" \
      && git clone https://github.com/dockerizedrupal/docker-base.git "${TMP}" \
      && cd "${TMP}" \
      && git checkout debian-wheezy \
      && sudo docker build -t dockerizedrupal/base:debian-wheezy . \
      && cd -

## License

**MIT**
