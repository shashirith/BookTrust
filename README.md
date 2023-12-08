# BookTrust📚

## Overview

The Decentralized Library Catalog Management System is a blockchain-based application that revolutionizes the way we manage book ownership and reading progress. Built on the Ethereum blockchain, it ensures transparent, tamper-proof, and secure tracking of books in a decentralized environment.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Project](#running-the-project)
- [Usage](#usage)
- [Smart Contract Deployment](#smart-contract-deployment)
- [Future Scope](#future-scope)
- [Acknowledgments](#acknowledgments)

## Features

- **Decentralized Ownership Tracking:** Utilizes Ethereum smart contracts for secure and transparent tracking of book ownership.
- **Reading Progress Management:** Allows users to update and track their reading progress for each book.
- **Efficient Book Retrieval:** Provides functions to retrieve finished and unfinished books for a user.
- **User-Friendly Interface:** Implemented with ReactJS to offer an intuitive and seamless user experience.

## Technologies Used

- **Ethereum Blockchain:** The backbone of the system, ensuring transparency and immutability.
- **Solidity:** A programming language for smart contracts.
- **Alchemy:** A platform for blockchain infrastructure, ensuring a reliable connection to the Ethereum network.
- **Hardhat:** A development environment for Ethereum that aids in compiling and deploying smart contracts.
- **Ether.js:** A JavaScript library for interacting with the Ethereum blockchain.
- **ReactJS:** A JavaScript library for building user interfaces.

## Getting Started

### Prerequisites

- Node.js and npm: [Install Node.js](https://nodejs.org/)
- Hardhat: Install globally using `npm install -g hardhat`

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/[your-username]/decentralized-library.git
    ```

2. Change directory:

    ```bash
    cd decentralized-library
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

### Running the Project

- Start the ReactJS front-end:

    ```bash
    npm start
    ```

- Deploy smart contracts on the Ethereum network:

    ```bash
    npx hardhat run scripts/deploy.js --network 
    ```

## Usage

The decentralized library system is easy to use. Users can add books, update reading progress, and retrieve book lists based on completion status through the user-friendly interface.

images of the project
<div align="center">
  <img width="433" alt="Screenshot 2023-12-08 at 7 24 38 PM" src="https://github.com/shashirith/BookTrust/assets/76678053/75215d9a-db1e-429e-8c04-083d37b313cb">
  <img width="252" alt="Screenshot 2023-12-08 at 7 26 56 PM" src="https://github.com/shashirith/BookTrust/assets/76678053/dfebec05-c06c-44ec-b414-2a3b301b2fd4">
 <img width="199" alt="Screenshot 2023-12-08 at 7 26 40 PM" src="https://github.com/shashirith/BookTrust/assets/76678053/82b84599-5d6c-4c0d-b8fd-79d8f1ea17a9">
 <img width="1003" alt="Screenshot 2023-12-08 at 7 25 41 PM" src="https://github.com/shashirith/BookTrust/assets/76678053/b85485b9-543b-4988-bdc2-2c2c93f9f760">
</div>

## Smart Contract Deployment

To deploy smart contracts to the Ethereum blockchain, use Hardhat and Alchemy. Ensure you have the necessary Ethereum network selected in your deployment script.


npx hardhat test

## Future Scope

- **Interoperability with Other Libraries:** Enable collaboration with other decentralized libraries.
- **NFT Integration:** Explore the integration of Non-Fungible Tokens for unique book representations.
- **Smart Recommendations:** Implement a recommendation system based on user reading history.
- **Mobile Apps and Accessibility:** Develop mobile applications for wider accessibility.

## Acknowledgments

I would like to express my gratitude to the following individuals and communities for their contributions, support, and inspiration:

- The [Ethereum community](https://ethereum.org/) for their valuable resources and documentation.
- [React Js](https://react.dev/) you have used or learned from.

Your support has been instrumental in the development of this project.


