# chainlink-balancemonitor
## Setup remix
Goto https://remix.ethereum.org/
Click the workspaces and click clone
use this repo to clone from https://github.com/chainlayer/chainlink-balancemonitor

## Compile and run
In the file explorer click EthBalanceMonitor.sol
Goto solidity compiler on the left and click "Compile EthBalanceMonitor"
Goto Deploy & Run and deploy the contract. For the two parameters
- Keeper Registry Address: Set this to the "Topup Caller" Address 0x38E5EB34D0785a171B7d05aF940d1Fe08f0CDcAa
- Minwaitperiodseconds: Set this to 60 (or higher if you want more time between two consecutive topups)

Once deployed add the contract and topup addresses to the repo here to make the contract caller work automatically
https://github.com/chainlayer/accounting-scripts
