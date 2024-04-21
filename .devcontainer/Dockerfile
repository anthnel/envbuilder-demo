FROM ubuntu

RUN apt-get update
RUN apt-get install vim sudo curl zsh -y

RUN useradd -m -s /bin/zsh -G sudo coder
USER coder