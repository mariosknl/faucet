# Variables

- uint(uint256) = 01010001200.... => 256 // only positive numbers
- int(int256) = 001010110101.... => 256 // positive and negative numbers

the 1st number (after the =) determines if it's positive or negative

uint

- min: 0
- max: 2^256 - 1

int

- min: -2^255
- max: 2^255 - 1

uint32

- max: 2^32 - 1

web3 js library to connect with Eth blockchain

web3.js: is a collections of libs that allow you to interact with a local or remote ethereum node

## Block info

- nonce => a hash that when combined with the minihash proofs that
  the block has gone through proof of work (POW)
- 8 bytes => 64 bits
