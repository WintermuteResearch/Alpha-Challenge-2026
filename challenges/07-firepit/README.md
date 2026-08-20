# Firepit - Tier 3

Uniswap turned on protocol fees last year as part of the ["UNIfication"](https://blog.uniswap.org/unification). Searchers can burn UNI and "release" the fees to themselves. What's not to like?
The hard part is finding a token jar worth your while. Luckily, the accumulated fees on X Layer seem to provide that opportunity... 

Can you execute a burn on X Layer and end up with 45,000 USD₮0 in your wallet?

Your wallet has been provided with 2,000 UNI at block 68413600.
## Setup

This challenge forks X Layer at block 68413600. Add an RPC to `.env`:

```
XLAYER_RPC_URL=https://rpc.xlayer.tech
```

Then:

```
python alpha.py check 06
```
