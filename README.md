# Binary for pinentry-mac

For some reason after updating to MacOS Sierra I was not able to install
`pinentry-mac` from homebrew without having `Xcode` installed. Since I don't
want to have `Xcode` installed, I compressed the binary from my old mac, so I 
could use it on my current Mac.

## Install guide
1. Make sure you have [homebrew](https://brew.sh) installed. 
2. Unzip the `pinentry-mac.zip` to `/usr/local/Cellar/`
3. `cd /usr/local/bin/`
4. Run `ln -sf ../Cellar/pinentry-mac/0.9.4/bin/pinentry-mac .`
5. Enjoy

## Notes
1. Make sure you verify this commit with my key: `0xF2403AC05942EE08`
2. Sha256: `091da2ab47a61df43c71d263edb322c745bd6048ea72e78ea584a60639620fb7  pinentry-mac.zip`

## License
I do not own the source code of `pinentry-mac`. You can find it's license [here](https://github.com/GPGTools/pinentry-mac)
