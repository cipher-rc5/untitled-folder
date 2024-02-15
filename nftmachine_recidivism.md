# Recidivism Analysis of NFTMachine

## Event Overview

In February 2021, an individual known as Tyler Gaye, operating under the alias NFTMachine (@boobs_scary), engaged in fraudulent activities by soliciting $500,000 USD from investors. The funds were purportedly for developing a website to facilitate transactions of non-fungible digital assets in exchange for 'ONFT Tokens' (**OpeNFT**), identifiable by the Ethereum blockchain address `0x869e54f7fe67af15eb0ed6e80358a248153a73db`. Despite collecting the funds, Tyler failed to deliver on his promises, leading to legal action by the investors. Although the court ruled in favor of the investors, mandating Tyler to compensate $275,000 USD, he defaulted on his court appearance and continued his fraudulent schemes, including launching Arcade DAO `0x78d1410B8483C9B50D3aBc1B1220BE49505b21e6`, which involved copyright infringement of the popular video game "Super Mario Bros".

Tyler Gaye's activities have not ceased post-lawsuit; he has initiated over ten projects to date, displaying awareness of his fraudulent actions and even threatening individuals on social media platforms, showing no remorse or intention to halt his fraudulent conduct.

## Scammer Profile

- **Name:** Tyler Gaye
- **Aliases:** NFTMachine, @boobs_scary
- **Email:** [tylercgaye@gmail.com](mailto:tylercgaye@gmail.com)
- **GitHub:** [https://github.com/tgaye](https://github.com/tgaye)

### Cryptocurrency Addresses

- Ethereum: `0x869e54f7fe67af15eb0ed6e80358a248153a73db` (OpeNFT.eth, sourced from [Rarible](https://rarible.com/nftmachine/owned))
- Solana: `8C4nNMisTKw9XwGhoK7GodMuwPWd3FPZPEis9KDDEnUt` (Connected to [TestNFT Gameframe](https://solana.fm/address/Hm1sPe2oEjgvFhBewwZmhszw9wd11v2qvBL8VDRrNH47) on GitHub)

**Warning:** High volume of transactional activity linked to additional addresses and Ethereum smart contracts.

### Associated Addresses

- address, network, name/label
- `0x78d1410B8483C9B50D3aBc1B1220BE49505b21e6`, eth, ArcadeDAO
- `0xaa9772d31476E85FedD1099E40dD2Ff5DEE214ff`, eth, 👑prince.eth
- `0x72feF29f03f8b678DB70410956537ffFdAF3e0a7`, eth, scaredofboobs.eth
- `0x8d6B69130e85E6E3b71f3987851455dd7CbF11Ca`, eth, mariobro.eth
- `0xa6c91C968c937c9626D4ce161F57082427336EB7`, eth, flappygames.eth
- `0xff68b0344E5D7136Db8DAc70Bdb3a6456C435d13`, eth, BloonsNFTs
- `0x892F10319A63eb27c22D1422b162BA85cb5Fbf18`, eth, test2034
- `0x5C9135255F8C5631f77aA1bb660d8128F6A02fF4`, eth, kraken_deposit(0x5C9)
- `0x2cE20a610d5C52285a05359e682F58B3DF95784b`, eth, pervcoin_deployer
- `0xdCF2629e8aeD1ACa339fbBC45AC2647608D3564F`, eth, @ETHarcade_NFT
- `0x2da4e94ae02c70fae4b2992f797a67e8f4c0c5fb`, eth, milady_beetles_funding
- `0xaf3ae19d40bD2311eE95e4F92B019F9552D1C4f6`, eth
- `0x78Af7C2f7bF33D97219a2746b87F9A7b99Fb60e1`, eth
- `0x91C8a2EB72a7eB5e3CdB1D58B3e61b251e25274C`, eth
- `0xC40D8f6e4f096B4A23483E45B8F907a3ED4766Cb`, eth

### Projects and Contracts

- `0xc35C2C682d4EE43D947228E3720a51fc3b8733B8`, Ethereum, NFT Machine Token
- `0xc35C2C682d4EE43D947228E3720a51fc3b8733B8`, ethereum, NFT Machine Token
- `0xa51EFb8E7D96B2936a95f9d4C6B30Df5956264B1`, ethereum, ETHarcade(ARCADE)
- `0x70A466bc212a0A4298BCA56195290242eBC61B18`, ethereum, ETHarcade(ARCADE)
- `0xbcca8ac7025cf59479d6b99aadcaee8b25ab122b`, ethereum, PlayerOne(ARCADE)
- `0x6e320ae6d5f96ddad224b191a3b5ebd058aab2fa`, ethereum, Pervcoin
- `0x7EAB971008DdC7c27fa24E077d24aA40aE51852B`, ethereum, PERV(PERV)
- `0xcc589aca361a41e7541433d54d8df06531991d24`, ethereum, Milady BEETLES
- `0x45fFCAFbD82B28Bf34f862092F2413003D960960`, ethereum, CryptoOGs
- `0xcb927b1bb7775cf4865cfd326b634979df02d7a4`, ethereum, Bloons
- `0x9a2abacd20885c1645d2d4e86e41493c73e0c5cb`, ethereum, bettle_game
- `0x92715b8F93729c0B014213f769EF493baecE`, etherum, Wifu

### Deployment Pattern
NFTMachine would commonly employ the mintToAdmin function:

- Function: mintToAdminMany(address _to,uint256_amount)
- MethodID: 0x68be561b
  - transaction sample from `0x78d1410B8483C9B50D3aBc1B1220BE49505b21e6` to ETH Arcade `0xa51EFb8E7D96B2936a95f9d4C6B30Df5956264B1`
    - eth txn: 0x289c8e108e73af7a469fca3ec52d61ba16237148ed046c2b618c4e2ce55cb5d1

### Known Scam Progression

Tyler's scam operations have transitioned across multiple platforms and projects, from OpeNFT to Arcade DAO, then to GamerGear, Solana, and back to Ethereum. He frequently used the `mintToAdminMany` function to allocate tokens to himself or associates, as evidenced by transactions like `0x289c8e108e73af7a469fca3ec52d61ba16237148ed046c2b618c4e2ce55cb5d1`.

## Sources and References

- [Investor lawsuit details](https://businessden.com/2022/05/24/investors-say-denver-nft-artist-stole-500k-spent-it-on-pixelated-cat-art/)
- [GitHub repositories](https://github.com/tgaye)
- [On-chain research by ZachXBT](https://x.com/zachxbt/status/1590049935692828673?s=20)
- [Copyright infringement case](https://beincrypto.com/arcade-dao-under-fire-alleged-scam-copyrighted-material/)
- [openft announcement](https://github.com/district0x/district-proposals/issues/295)
- [Github](https://github.com/tgaye)
- [bloons-nf-tmint](https://urlscan.io/result/d0260fbd-5b2b-4aab-b7e4-6981e5caec2e/)
- [Flappyroyale](https://urlscan.io/result/7c0437cf-3d86-403f-b3ea-ce1f1f8ce8ef/)
- [0penft github](https://github.com/0peNFT)
- [0xShual Research](https://x.com/0xShual/status/1739230667047686581?s=20)
- [2021_Overview_Summary](https://businessden.com/2022/05/24/investors-say-denver-nft-artist-stole-500k-spent-it-on-pixelated-cat-art/)
- [Openft medium introduction](https://openft.medium.com/introducing-openft-the-first-community-owned-crypto-art-aggregator-bc50cfb359af)
- [Openft Medium](https://openft.medium.com/)
- [Legal_docs_2021](https://trellis.law/doc/163654158/order-related-document-order-granting-substituted-service-granted)
- [Copyright infringement of MarioBros](https://beincrypto.com/arcade-dao-under-fire-alleged-scam-copyrighted-material/)
- [Overview](https://www.bitcoininsider.org/article/192978/nft-scammer-fined-275000)

## Address interactions visualization

[Visualization available here](https://metasleuth.io/result/eth/0x01b07c638abf4320d8fddcb62ff24267687c4a2f2609f195c1de4c185f41fa7b?source=6ec4172b-fde1-4373-8dce-b2d0ccb123d0)

### Contact Information

**Judge David Goldberg**
Colorado District Court
[https://www.courts.state.co.us/Bio.cfm?Employee_ID=808](https://www.courts.state.co.us/Bio.cfm?Employee_ID=808)
