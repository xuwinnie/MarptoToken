1. deploy two token contracts, refer to layerzeroEndpoints.json
2. call `setTrustedRemoteAddress` with coresponding token address and chain id
3. call `estimateSendFee` to estimate fee for cross chain transfer
4. call `sendfrom` to do cross chain transfer

PS: call `mint` to mint up to 26% unallocated tokens
PPS: call `renounceOwnership` (after step 2) to freeze supply and reduce centralization concerns
PPPS: call `release` at vesting wallets to unlock tokens

Reference: https://layerzero.gitbook.io

by winnie :)