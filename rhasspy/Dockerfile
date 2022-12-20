FROM rhasspy/rhasspy:2.5.11
LABEL maintainer="Daniele Stakanov Senatore <senatoredaniele@gmail.com>"

ENV LANG C.UTF-8

ENV CONFIG_PATH /data/options.json

# Copy data for add-on
COPY run.sh /
RUN chmod a+x /run.sh

CMD ["/run.sh"]
