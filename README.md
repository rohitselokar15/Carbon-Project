# Carbon-Project

## Summary

The Carbon-Project aims to establish a Carbon Credit Ecosystem on the Ethereum blockchain, enhancing liquidity, transparency, accessibility, and standardization in carbon markets. The ecosystem includes stakeholders, a tokenization mechanism (ERC20) with clear minting and burning protocols, transparent token distribution, and a free automated market maker (AMM) for trading carbon tokens. Additionally, we issue Ethereum-based non-fungible tokens (NFTs) as carbon removal certificates for verified carbon credit usage.

## Background

Climate change and global warming pose significant challenges, and the Kyoto Protocol (1997) emphasizes market mechanisms to address greenhouse gas emissions. Carbon trading systems treat carbon dioxide emissions as commodities, with carbon offsetting crucial for meeting the goals of the Paris Climate Agreement. However, global adoption is hindered by transparency issues. The Carbon-Project addresses this by leveraging blockchain technology to provide transparency in the issuance, usage, and life cycle of carbon credits.

## Project Description

The ecosystem involves various stakeholders, including Generators (carbon credit producers), Consumers (emitters or polluters), Validators (accredited consultants), and other participants. Validators play a key role in onboarding projects to an open architecture marketplace. Carbon credits are converted to ERC-20 tokens, distributed to generators, and traded on a decentralized exchange platform. Tokens are retired through a "buy and burn" model, and successful participants receive Ethereum-based NFTs as carbon removal certificates.

## Technical Description

1. **carboncredits.sol**: Creates a registration template for three groups: Verifiers, Creditholders, and Customers. Verifiers validate credits, Creditholders own credits, and Customers offset their carbon footprint by buying and burning carbon tokens.

2. **credittoken.sol**: Implements an ERC20 token based on approved carbon credits. Functions include approving credits, minting carbon tokens, and making them transferable and burnable.

3. **certification.sol**: Generates ERC721 tokens (NFTs) as certificates for burning carbon tokens. An NFT is minted for every 20 carbon tokens burnt, symbolizing successful carbon emission offsetting.

4. **Balancer Smart Pool (AMM)**: Creates a smart pool with a swappable DAI - Carbon token pair. Incentives for liquidity providers include transaction fees, and dynamic pricing for the Carbon token is established within the pool.


## Contributors

We welcome contributions! Feel free to open issues, submit pull requests, or join our discussions.
