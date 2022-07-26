# rust programming : mint token for spl-token

# build
cargo build

# run
cargo run cluster keypair(file) decimals mint_amount

cluster: devnet or mainnet

# example - devnet, 8 decimals spl-token, mint 10
cargo run devent ./account.json 8 10000000000