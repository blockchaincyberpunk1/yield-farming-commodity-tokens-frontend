# Yield Farming Commodity Tokens Frontend

This directory contains the frontend components for the Yield Farming Commodity Tokens project. These components provide the user interface for interacting with the smart contracts deployed on the Ethereum blockchain.

## Summary

The frontend consists of several components designed to facilitate the interaction with the smart contracts:

1. **CommodityTokenInterface.jsx**: Provides an interface for users to view commodity-backed token balances and interact with the token contract.

2. **RewardDistribution.jsx**: Displays the distribution of rewards to stakers and allows the contract owner to initiate reward distribution.

3. **StakeForm.jsx**: Allows users to stake commodity-backed tokens into the yield farming contract.

4. **UnstakeForm.jsx**: Allows users to withdraw their staked tokens from the yield farming contract.

5. **YieldFarmingInterface.jsx**: Integrates all components to create the main user interface for the yield farming functionality.

6. **ethersService.js**: Contains utility functions for interacting with the Ethereum blockchain using the Ethers.js library.

## Setup and Usage

1. Install dependencies using `npm install` or `yarn install`.
2. Start the development server using `npm start` or `yarn start`.
3. Access the application in your web browser at the specified URL.

Ensure that the backend server and smart contracts are deployed and accessible to the frontend application.

## Components

- **CommodityTokenInterface.jsx**: Interface for viewing token balances and interacting with the token contract.
- **RewardDistribution.jsx**: Display and initiate reward distribution to stakers.
- **StakeForm.jsx**: Form for staking tokens into the yield farming contract.
- **UnstakeForm.jsx**: Form for withdrawing staked tokens from the yield farming contract.
- **YieldFarmingInterface.jsx**: Main interface integrating all components for yield farming functionality.
- **ethersService.js**: Utility functions for interacting with the Ethereum blockchain.

## License

The frontend components are provided under the MIT License. See individual files for details.
