FROM alekna/openbox-desktop-vnc:latest
MAINTAINER ME

RUN dnf install -y wine tar gzip unzip && dnf clean all

CMD ["ln", "-s", "/wine/ea", "/wine/XM\ MT4/MQL4/Experts/ea"]
#ADD wine.zip /
#WORKDIR /
#RUN unzip wine.zip