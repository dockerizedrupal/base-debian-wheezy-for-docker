# docker-base-debian-wheezy

## Build the image

    TMP="$(mktemp -d)" \
      && git clone https://github.com/dockerizedrupal/docker-base-debian-wheezy.git "${TMP}" \
      && cd "${TMP}" \
      && git checkout 1.0.0 \
      && sudo docker build -t dockerizedrupal/base-debian-wheezy:1.0.0 . \
      && cd -

## License

**MIT**
