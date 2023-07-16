<!-- PROJECT SHIELDS -->

[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->

<br />
<div align="center">
  <a href="#">
    <img src="https://firebasestorage.googleapis.com/v0/b/virtualground-meta.appspot.com/o/nft%2Fnft.png?alt=media&token=58741d5d-9f34-4884-a30e-3cb24c0f2028" alt="Logo" width="120" height="50">
  </a>

  <h3 align="center">NFT Marketplace</h3>
  <a href="https://marketplace-46f99.web.app/">Link</a>

</div>

<!-- ABOUT THE PROJECT -->

## About The Project

<p align="left">
    An awesome marketplace to turn your products or services into publicly tradeable items.
</p>

#### Network

Contract is deployed on Polygon mumbai network

```sh
Marketplace Address: 0xFC825b8f07E465c32b199Ecf5b0f3B679A4285b0
RPC URL: https://rpc-mumbai.maticvigil.com
```

https://mumbai.polygonscan.com/address/0xFC825b8f07E465c32b199Ecf5b0f3B679A4285b0

### ⚙️Functions:

- Web3 auth using metamask🦊/walletconnect/coinbase
- Create & list tokens for sale
- Using IPFS for uploading the file📁
- Marketplace owner can set platform fee
- Buyer can purchase token and list it again for sale

<img src="images/Prev1.png" width="45%"></img>
<img src="images/Prev2.png" width="45%"></img>
<img src="images/Prev3.png" width="45%"></img>
<img src="images/Prev4.png" width="45%"></img>

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

- [Next.js](https://nextjs.org/)
- [Material UI](https://mui.com/)
- [Hardhat](https://hardhat.org/)
- [Solidity](https://docs.soliditylang.org/)

<p align="right">(<a href="#top">back to top</a>)</p>

### Installation

Below are instructions to get started

1. Clone the repo
   ```sh
   git clone https://github.com/ac12644/NFT-Marketplace.git
   ```
2. Install packages
   ```sh
   yarn
   ```
3. Add environment variables, also you will require dedicated subdomain for IPFS from infura
   ```sh
   PRIVATE_KEY=
   MUMBAI_URL= https://rpc-mumbai.maticvigil.com/
   INFURA_IPFS_ID=
   INFURA_IPFS_SECRET=
   INFURA_IPFS_DOMAIN=
   ```
4. Deploy smart contract
   ```sh
   npx hardhat run scripts/deploy.js --network mumbai
   ```
5. Run application
   ```sh
   yarn run dev
   ```


<p align="right">(<a href="#top">back to top</a>)</p>
 
 
<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

[forks-shield]: https://img.shields.io/github/forks/ac12644/NFT-Marketplace?style=for-the-badge
[forks-url]: https://github.com/ac12644/NFT-Marketplace/network/members
[stars-shield]: https://img.shields.io/github/stars/ac12644/NFT-Marketplace?style=for-the-badge
[stars-url]: https://github.com/ac12644/NFT-Marketplace/stargazers
[issues-shield]: https://img.shields.io/github/issues/ac12644/NFT-Marketplace?style=for-the-badge
[issues-url]: https://github.com/ac12644/NFT-Marketplace/issues
[license-shield]: https://img.shields.io/github/license/ac12644/NFT-Marketplace?style=for-the-badge
[license-url]: https://github.com/ac12644/NFT-Marketplace/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/ac12644/
