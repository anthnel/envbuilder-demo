FROM ubuntu

RUN apt-get update \
    && apt-get install vim sudo curl zsh -y \
    && rm -rf /var/lib/apt/lists/*

RUN useradd -m -s /bin/zsh -G sudo coder
USER coder