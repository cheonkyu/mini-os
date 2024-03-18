

https://os.phil-opp.com/freestanding-rust-binary/#introduction


```
rustup component add llvm-tools-preview.
rustup toolchain install nightly --component llvm-tools-preview
```


```
brew install qemu
```

```
qemu-system-x86_64 -drive format=raw,file=target/x86_64-mini-os/debug/bootimage-mini-os.bin
```