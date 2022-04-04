# EVM Draw Contract

This draws each byte of bycode in an EVM contract, allowing you to get a quick overview of the shape of a smart contract.

## To Install

It's written in nim. You will need to install nim, and the one dependency that the code will complain about.

## To Use

To use:

Edit the source to add the contract bytecode (without the leading 0x), then run:

    nim compile --run evm_contract_draw.nim

This will print the name of the newly created image file.

## Contributions

Contribute away! DM me on twitter (@DanielVF) if you make a PR - my email is overloaded.

Wishlist:

- Should be able take contract bytecode from std in
- Seperate layout code from drawing code
- Better install instructions
- HTML output option with per instruction tooltips.