hal -- the Bitcoin companion
============================

hal is a command line tool that provides all kinds of Bitcoin-related utilities.


# Summary of commands:

- address
	- inspect: get information about addresses
	- create: create addresses using public keys or scripts

- bip32
	- derive: derive keys and addresses from extended keys

- ln
	- invoice
		- decode: decode Lightning invoices

- psbt
	- create: create a PSBT from a raw unsigned transaction
	- decode: decode a PSBT to JSON
	- edit: edit a PSBT inline
	- merge: merge multiple PSBTs into one

- script
	- decode: decode a PSBT to JSON
	- coming soon: script descriptor support

- tx
	- create: create a binary transaction from JSON
	- decode: decode a binary transaction to JSON

More to come!

Ideas:
- (extended) private key generation
- optional [Trezor](https://github.com/stevenroose/rust-trezor-api/) and Ledger integration
- Liquid support
