# README

This Solana program is designed to handle Token Presale. It provides functionalities such as initializing the IDO, buying tokens, refunding tokens, updating the presale period, and more.
Instructions

The program's instructions are defined in the instructions module. Here's a brief overview of each instruction:

## Initialize

This instruction is used to initialize the IDO. It sets up the necessary accounts and assigns the super admin.

## Buy Token

This instruction allows a user to buy tokens from the IDO. The user's SOL is transferred to the escrow account, and the user's token balance is updated.

## Refund Token

This instruction allows a user to refund their tokens. The user's tokens are returned, and their SOL is transferred back from the escrow account.

## Cancel Presale

This instruction allows the admin to cancel the presale. Once cancelled, no further operations can be performed on the presale.

## Update Presale Period

This instruction allows the admin to update the presale period. The start and end times of the presale can be updated.

## Deposit Token

This instruction allows the admin to deposit tokens into the presale. The tokens are transferred from the admin's account to the token vault.

## Withdraw

This instruction allows the admin to withdraw SOL from the escrow account after the presale has ended.

## Set Whitelist

This instruction allows the admin to enable or disable the whitelist feature.

## Add Whitelist

This instruction allows the admin to add addresses to the whitelist.

## Remove Whitelist

This instruction allows the admin to remove addresses from the whitelist.

## Finalize

This instruction allows the admin to finalize the presale. Once finalized, no further operations can be performed on the presale.

