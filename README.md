# decentralized-nft-lottery

Project Documentation: Decentralized NFT Lottery System
Overview

This project proposes the development of a decentralized lottery system utilizing Non-Fungible Tokens (NFTs) and Chainlink Price Feeds and VRFs. The system will enable participants to enter the lottery using various cryptocurrencies, receiving unique digital assets as lottery tickets and rewards.
Key Features

    NFT-Based Lottery Tickets:
        Standard Tickets (ERC1155): Participants purchase standard lottery tickets represented as ERC1155 tokens.
        Special Tickets (ERC721): Limited edition tickets, offering potential additional benefits, represented as ERC721 tokens? (Could be ERC1155 too).

    Winner's Reward (ERC721 NFT):
        Unique ERC721 NFTs minted for lottery winners, serving as both a proof of winning and a collectible.

    Multi-Token Participation via Chainlink Price Feeds:
        Acceptance of various cryptocurrencies for ticket purchase, with conversion rates provided by Chainlink Price Feeds. Lottery balance will be in ETH.

Implementation Strategy
Smart Contract Development

    Lottery Contract: Manages the lottery logic, including ticket sales, winner selection, and prize distribution.
    NFT Contracts: Handles the minting and tracking of ERC1155 and ERC721 tokens.
    Chainlink Integration:
        VRF (Verifiable Random Function): Ensures fair and random winner selection.
        Price Feeds: Facilitates ticket pricing in various cryptocurrencies.

Front-End Development

    User Interface: Developed with React/Next.js, featuring:
        Options for viewing and purchasing lottery tickets.
        Display of owned NFTs (tickets and rewards).
        Selection of payment options and real-time price conversion display.

Testing and Deployment

    Sepolia Testnet Deployment: The system will be initially deployed on the Sepolia testnet for testing, debugging, and gathering user feedback. Still deciding whether this project will be done in Hardhat or Foundry.
