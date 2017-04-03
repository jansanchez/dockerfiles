FROM yantis/wine
LABEL maintainer "Jan Sanchez <joejansanchez@gmail.com>"

CMD mkdir -p /tmp/shared && chmod -R 755 /tmp/shared

ENV APP PhotoshopCS5

RUN echo "wine /usr/src/$APP/$APP.exe" > /root/.bash_history

CMD [ "bash" ]
