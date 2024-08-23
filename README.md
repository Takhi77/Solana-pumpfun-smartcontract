# Pump.fun-Smart-Contract
This is the Rust/Anchor smart contract for Pump.fun.

## Features
It has All features that pump.fun has.
✅ Token Mint
✅ Create Pool with 30 Sol of initial virtual Sol reserve
✅ Add Liquidity
✅ Swap Token with the price of the token (Virtual Sol Reserve / Virtual Token Reserve)
✅ Raydium Launch when the Market Cap of the Token (price of the token * 10 ** 9) is reached to $69M

It has its own test cases to test all functions except Raydium Launch because it is used my ongoing project.
You can check the tx to Remove vitual LP and Create Raydium Pool in this smart contract with CPI calls.
https://explorer.solana.com/tx/4L6MWmtV1ZsT8NFfbtu68ZYyYVbpvZ4iynJhPdZw8jESi28TxwojjTFs88Q5QRdNUb297aWfkKcoYP9Ya8npx8AV?cluster=devnet
In this smart contract, I set creating LP FEE as 5% of Reserves.

### If you have any questions, then contact me with the info in my profile.
