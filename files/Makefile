rustup: rbuild
parity: pbuild

rbuild:
	curl https://sh.rustup.rs -sSf | sh -s -- --default-toolchain stable -y

pbuild:
	git clone https://github.com/paritytech/parity && \
	cd parity  && \
	cargo build --release
        
