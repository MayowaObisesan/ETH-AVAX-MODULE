# ETH AVAX THIRD MODULE - ERC20 Tokens

This is the third module of the ETH_AVAX MetaCrafter Challenge.
The assessment is to create and deploy an ERC20 Token which will do the following.

- Only contract owner should be able to mint tokens
- Any user can transfer tokens
- Any user can burn tokens

## Description

In the contract, I made use of three OpenZeppelin contracts:

- The Ownable
- The ERC20
- The Burnable; Contracts

**The Ownable contract** for the OnlyOwner modifier that ensures that only the owner of the contract, in the case of this contract, the user that deployed the contract can mint.

**The ERC20 contract** for ERC20 standard functions such as burn, mint, transfer, transferFrom, etc.

**The Burnable Contract** to allow users to burn their own tokens.

Here is the link to the [deployed contract](https://sepolia.etherscan.io/address/0x3ebf4fa405985f3d11f21840e3fdde69937f2d40)
