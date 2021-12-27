# Muesli Factory

MuesliSwap smartBCH has been renamed to CowSwap. The smart contracts stay the same and have been [audited by TechRate](https://github.com/TechRate/Smart-Contract-Audits/blob/main/October/MuesliSwap.pdf).

Core contracts of CowSwap. Forked from Uniswap.

### Verify deployed contracts
You can verify that the deployed Muesli contracts are matching with this repo using a provided Python script.
Usage:
```
yarn && yarn compile  # in all repos (core, periphery, farming)
# pip3 install web3  # if you don't have it
python3 verify_deployed.py
```
