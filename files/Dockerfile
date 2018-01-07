FROM ubuntu:16.04
ARG rustup_version=stable
ARG parity_version=stable
RUN apt-get update
RUN apt-get install -y git make gcc g++ libssl-dev openssl libudev-dev pkg-config curl
WORKDIR /home
COPY Makefile .
RUN make rustup rustup_version
ENV PATH=/root/.cargo/bin:$PATH
RUN make parity parity_version
# CMD ["cp","parity/target/release/parity", "release/parity"]