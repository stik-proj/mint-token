# rust programming : mint token for spl-token

# build
cargo build

# run
cargo run cluster keypair(file) decimals mint_amount
- cluster: devnet or mainnet

## Devnet, 9 decimals spl-token
cargo run devent ./account.json 9 250000000

## Mainnet, 9 decimals spl-token
cargo run mainnet ./account.json 9 250000000
