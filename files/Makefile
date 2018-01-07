rustup: rbuild
parity: pbuild

rbuild:
	curl https://sh.rustup.rs -sSf | sh -s -- --default-toolchain $(rustup_version) -y

pbuild:
	git clone -b $(paraty_version) https://github.com/paritytech/parity && \
	cd parity  && \
	cargo build --release
        
