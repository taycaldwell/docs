---
slug: /solana/react
title: react package
hide_title: true
displayed_sidebar: react
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## react package

## Functions

| Function                                                                       | Description                                                                                                                                                 |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [balanceQuery(sdk)](./react.balancequery.md)                                   |                                                                                                                                                             |
| [claimConditionsQuery(program)](./react.claimconditionsquery.md)               |                                                                                                                                                             |
| [dropTotalClaimedSupplyQuery(program)](./react.droptotalclaimedsupplyquery.md) |                                                                                                                                                             |
| [dropUnclaimedSupplyQuery(program)](./react.dropunclaimedsupplyquery.md)       |                                                                                                                                                             |
| [nftCreatorsQuery(program)](./react.nftcreatorsquery.md)                       |                                                                                                                                                             |
| [nftGetAllQuery(program, queryParams)](./react.nftgetallquery.md)              |                                                                                                                                                             |
| [nftRoyaltyQuery(program)](./react.nftroyaltyquery.md)                         |                                                                                                                                                             |
| [nftTotalSupplyQuery(program)](./react.nfttotalsupplyquery.md)                 |                                                                                                                                                             |
| [programAccountTypeQuery(sdk, address)](./react.programaccounttypequery.md)    |                                                                                                                                                             |
| [programMetadataQuery(program)](./react.programmetadataquery.md)               |                                                                                                                                                             |
| [programQuery(queryClient, sdk, address, type)](./react.programquery.md)       |                                                                                                                                                             |
| [tokenBalanceQuery(program, walletAddress)](./react.tokenbalancequery.md)      |                                                                                                                                                             |
| [tokenSupplyQuery(program)](./react.tokensupplyquery.md)                       |                                                                                                                                                             |
| [useBalance()](./react.usebalance.md)                                          | Get the currently connected wallet balance                                                                                                                  |
| [useBurnNFT(program)](./react.useburnnft.md)                                   | Burn an NFT owned by the connected wallet                                                                                                                   |
| [useClaimConditions(program)](./react.useclaimconditions.md)                   | Get the current claim conditions on an NFT Drop                                                                                                             |
| [useClaimNFT(program)](./react.useclaimnft.md)                                 | Claim NFTs from an NFT Drop program                                                                                                                         |
| [useCreators(program)](./react.usecreators.md)                                 | Get the creators for an NFT program                                                                                                                         |
| [useDropTotalClaimedSupply(program)](./react.usedroptotalclaimedsupply.md)     | Get the total claimed supply of NFTs on an NFT Drop                                                                                                         |
| [useDropUnclaimedSupply(program)](./react.usedropunclaimedsupply.md)           | Get the total unclaimed supply of NFTs on an NFT Drop                                                                                                       |
| [useLazyMint(program, onProgress)](./react.uselazymint.md)                     | Lazy mint NFTs on an NFT Drop program                                                                                                                       |
| [useLogin(config)](./react.uselogin.md)                                        | **<i>(BETA)</i>** Hook to securely login to a backend with the connected wallet. The backend authentication URL must be configured on the ThirdwebProvider. |
| [useLogout()](./react.uselogout.md)                                            | **<i>(BETA)</i>** Hook to logout the connected wallet from the backend. The backend logout URL must be configured on the ThirdwebProvider.                  |
| [useMintNFT(program)](./react.usemintnft.md)                                   | Mint NFTs on your NFT program                                                                                                                               |
| [useMintNFTSupply(program)](./react.usemintnftsupply.md)                       | Mint additional supply for an NFT on your NFT program                                                                                                       |
| [useMintToken(program)](./react.useminttoken.md)                               | Mint tokens on your token program                                                                                                                           |
| [useNFTs(program, queryParams)](./react.usenfts.md)                            | Get the metadata for every NFT on an NFT program                                                                                                            |
| [useProgram(address, type)](./react.useprogram.md)                             | Get an SDK instance to interact with any program                                                                                                            |
| [useRoyaltySettings(program)](./react.useroyaltysettings.md)                   | Get the royalty for an NFT program                                                                                                                          |
| [useSDK()](./react.usesdk.md)                                                  |                                                                                                                                                             |
| [useSetClaimConditions(program)](./react.usesetclaimconditions.md)             | Set Claim Conditions to an NFT Drop program                                                                                                                 |
| [useTokenBalance(program, walletAddress)](./react.usetokenbalance.md)          | Get the token balance of a specified wallet                                                                                                                 |
| [useTokenSupply(program)](./react.usetokensupply.md)                           | Get the total circulating supply of a token                                                                                                                 |
| [useTotalSupply(program)](./react.usetotalsupply.md)                           | Get the totaly supply of NFTs on the program                                                                                                                |
| [useTransferNFT(program)](./react.usetransfernft.md)                           | Transfer NFTs from the connected wallet to another wallet                                                                                                   |
| [useTransferToken(program)](./react.usetransfertoken.md)                       | Transfer tokens from the connected wallet to another wallet                                                                                                 |
| [useUpdateCreators(program)](./react.useupdatecreators.md)                     | Update the creators for an NFT program                                                                                                                      |
| [useUpdateRoyaltySettings(program)](./react.useupdateroyaltysettings.md)       | Update the royalty for an NFT program                                                                                                                       |
| [useUser()](./react.useuser.md)                                                | **<i>(BETA)</i>** Hook to get the currently logged in user.                                                                                                 |

## Interfaces

| Interface                                       | Description |
| ----------------------------------------------- | ----------- |
| [LoginConfig](./react.loginconfig.md)           |             |
| [ThirdwebAuthUser](./react.thirdwebauthuser.md) |             |

## Variables

| Variable                                              | Description                                                                                                                                                                                                        |
| ----------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [ThirdwebProvider](./react.thirdwebprovider.md)       | **<i>(BETA)</i>** Gives access to the ThirdwebSDK instance and other useful hooks to the rest of the app. Requires to be wrapped with a ConnectionProvider and a WalletProvider from @solana/wallet-adapter-react. |
| [ThirdwebSDKProvider](./react.thirdwebsdkprovider.md) | Gives access to the ThirdwebSDK instance and other useful hooks to the rest of the app. Requires to be wrapped with a ConnectionProvider and a WalletProvider from @solana/wallet-adapter-react.                   |

## Type Aliases

| Type Alias                                                            | Description |
| --------------------------------------------------------------------- | ----------- |
| [TransferNFTMutationParams](./react.transfernftmutationparams.md)     |             |
| [TransferTokenMutationParams](./react.transfertokenmutationparams.md) |             |
| [UseProgramResult](./react.useprogramresult.md)                       |             |
