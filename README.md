# BitcoinZ - Your Financial Freedom
For more details check root [BitcoinZ repository](https://github.com/bitcoinz-pod/bitcoinz) 

### Windows

- Download Windows release binary [here](https://github.com/bitcoinz-pod/bitcoinz-win/releases)

or

- Build binaries (tested in Ubuntu 16.04)
Get dependencies
```{r, engine='bash'}
sudo apt-get install \
      build-essential pkg-config libc6-dev m4 g++-multilib \
      autoconf libtool ncurses-dev unzip git python \
      zlib1g-dev wget bsdmainutils automake mingw-w64
```

Install (Cross-Compiled, building on Windows is not supported yet)
```{r, engine='bash'}
# Build
./zcutil/build-win.sh --disable-rust -j$(nproc)
```
The exe will save to `src` which you can then move to a windows machine

Security Warnings
-----------------

**BitcoinZ is experimental and a work-in-progress.** Use at your own risk.
