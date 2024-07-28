This repo is based on solidity smart contracts.
I creates DOLA Token in which DOLA's value will be pegged to our upcoming token, ROI, with BDOLA as collateral.
The BDOLA is used as collateral for minting DOLA tokens. This mint function, where BDOLA tokens are transferred from the sender to the contract address as collateral.
 It uses Chainlink Price Feed to get the latest price of ROI and BDOLA.
 I also created the WRAP and UNRWAP Token
 The wrap function allows users to convert a specified amount of native tokens (in this case, EMPRESS TOKEN, EMP) into wrapped tokens (WTKN).
 It then mints the equivalent amount of WTKN to the user's address. The unwrap function allows users to convert wrapped tokens (WTKN) back
into their original form (native tokens, EMP).It then transfers the equivalent amount of native tokens back to the user's address.
