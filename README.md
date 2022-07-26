# rust programming : mint token for spl-token

# build
cargo build

# run
cargo run cluster keypair(file) decimals mint_amount

cluster: devnet or mainnet

# devnet, 9 decimals spl-token
cargo run devent ./account.json 9 10000000000