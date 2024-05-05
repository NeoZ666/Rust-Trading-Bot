# Rusting our Trades with a Low Latency Setup

## Pre-Req
- Docker installed
    - link: https://docs.docker.com/engine/install/
- Setup Bybit testnet api key
- Install VS code with rust-analyzer extension
    - VS code: https://code.visualstudio.com/download
    - rust-analyzer extension: https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer
    - Better TOML : https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml
    - crates : https://marketplace.visualstudio.com/items?itemName=serayuzgur.crates
    - Error Lens : https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens


## **cd into the Working Directory** 
    - run `docker build -t rust-bot .` 
1. Sign up a Bybit testnet account
    - link: https://testnet.bybit.com/
2. Enable 2FA in setting
3. Run `docker run -it --rm -v $PWD/src/:/home/src rust-bot` in the dir
