FROM homeassistant/armhf-base:latest
LABEL io.hass.version="0.47"
ENV LANG C.UTF-8

# Setup base
RUN apk add --no-cache git
RUN git clone https://github.com/50ButtonsEach/fliclib-linux-hci.git

CMD [ "/run.sh" ]