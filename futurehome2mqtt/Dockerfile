ARG BUILD_FROM
FROM $BUILD_FROM

ENV LANG C.UTF-8
ENV HOME=/app

RUN mkdir -p $HOME
WORKDIR ${HOME}


# Copy data for add-on
COPY ./ $HOME/

RUN chmod a+x /$HOME/run.sh


CMD [ "/app/run.sh" ]
