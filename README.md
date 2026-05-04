# Rust bindings for libxdp

#### Package
```bash
git submodule update --remote

cd xdp-tools && git checkout target_tag

cargo clean

cargo check

```

#### ENV Depend
```bash
apt install build-essential pkgconf zlib1g-dev libelf-dev -y

apt install clang llvm libelf-dev libpcap-dev build-essential -y

apt install libbpf-dev -y

apt install -y libcap2 libcap-dev

apt install libxdp-dev ( 可选 )

apt install libc6-dev-i386 ( 可选 )

apt install -y bc bison build-essential elfutils flex libdw-dev libelf-dev make ncurses-dev python3-docutils zstd

```

