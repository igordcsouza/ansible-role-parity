rustup:
	curl https://sh.rustup.rs -sSf | sh -s -- --default-toolchain $(rustup_version) -y

parity:
	git clone -b $(parity_version) https://github.com/paritytech/parity && \
	cd parity  && \
	cargo build --release
        
