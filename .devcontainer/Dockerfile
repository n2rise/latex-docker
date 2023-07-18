FROM paperist/alpine-texlive-ja:2021

RUN apk update && \
    apk upgrade && \
    apk add --no-cache bash git openssh && \
    touch ~/.bashrc
CMD ["/bin/bash"]
