FROM ubuntu:16.04
RUN apt-get update
RUN apt-get install -y git make gcc g++ libssl-dev openssl libudev-dev pkg-config curl
WORKDIR /home
COPY Makefile .
RUN make rustup
ENV PATH=/root/.cargo/bin:$PATH
RUN make parity
CMD ["cp","parity/target/release/parity", "release/parity"]