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

## Future Work

1. Integrating with Paper Trading Platforms using AzureDevops Pipeline for automated Trading.
2. Futures and Options Trading.
3. Learn more Rust.

## Feedback and Issues

If you encounter any issues or have feedback, please [submit an issue](https://github.com/NeoZ666/Rust-Trading-Bot/issues). Your inputs are appreciated!

## Contributing

Welcoming contributions from the community. Fork the repository, make your changes, and submit a pull request. See Github's [contributing guidelines](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors) for more details.
