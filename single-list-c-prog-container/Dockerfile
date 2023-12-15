FROM gcc:9-buster

COPY . /usr/src/cpp_files

WORKDIR /usr/src/cpp_files

RUN gcc -o prg prg.c

CMD ["./prg"]