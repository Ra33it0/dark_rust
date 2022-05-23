# dark_rust
Offensive rust Experiments.

Including practices of the book Black-Hat-Rust and other tools.

## Sha1cracker is a sha1 cracker for Bip39 words.

## Usage 
1. Take a word from the Bip39 wordlist.
- acid
2. Encode it https://v2.cryptii.com/text/sha1KD     434b0a6daa530638a964132e86b8a01d7b39aa7c
3. run the cracker on the hash 
cargo run -- wordlist.txt "434b0a6daa530638a964132e86b8a01d7b39aa7c"

