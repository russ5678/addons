FROM %%BASE_IMAGE%%

ENV LANG C.UTF-8

# Setup base
RUN apk add --no-cache git
RUN git clone https://github.com/50ButtonsEach/fliclib-linux-hci.git /flic
COPY run.sh /
RUN chmod a+x /run.sh
RUN chmod a+x /flic/bin/armv6l/flicd
CMD [ "/run.sh" ]