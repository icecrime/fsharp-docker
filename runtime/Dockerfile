FROM icecrime/fsharp
MAINTAINER Arnaud Porterie "icecrime@gmail.com"

WORKDIR /app
ONBUILD ADD . /app
ONBUILD RUN /usr/bin/fsharpc --out:Program.exe /app/*.fs

CMD []
ENTRYPOINT ["/usr/bin/mono", "Program.exe"]

