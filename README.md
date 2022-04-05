# EVM Draw Contract

This draws each byte of bycode in an EVM contract, allowing you to get a quick overview of the shape of a smart contract.

![Example image](https://user-images.githubusercontent.com/837/161564178-7e545f3f-f6ff-45ba-8f3a-b8ff915449e6.png)

## To Install

It's written in nim. 
1. You will need to install nim as mentioned here: https://nim-lang.org/install.html 

2. Install nimPNG package using the command:
```bash
nimble install nimPNG
```

## To Use

To use:

Edit the source to add the contract bytecode (without the leading 0x), then run:

    nim compile --run evm_contract_draw.nim

This will print the name of the newly created image file.

## Contributions

Contribute away! DM me on twitter at [@DanielVF](https://twitter.com/danielvf) if you make a PR - my email is overloaded.

Wishlist:

- Should be able take contract bytecode from std in
- Seperate layout code from drawing code
- Color themes
- Better install instructions
- Readme section to explain what this is showing  
- HTML output option with per instruction tooltips.
