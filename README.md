# Crowdfunding WebApp Test Stage1

# Deployed Features->

- > User can start a fundraising.
- > Anyone in the network can contribute.
- > Project ends if the target contribution amount is reached.
- > Project expires if targeted amount is not fulfilled till deadline.
- > Contributors can withdraw contributed amount if project expires.
- > Connect with wallet.


### Tech Stack & Packages used 📦

| package                                                             | explain                                                               |
| ------------------------------------------------------------------- | --------------------------------------------------------------------- |
| [Next.js](https://nextjs.org/docs/getting-started)                  | For building frontend                                                 |
| [solidity](https://docs.soliditylang.org/en/v0.8.13/)               | For writting smart contracts                                          |
| [tailwind css](https://tailwindcss.com/docs/installation)           | For building design                                                   |       
| [ether.js](https://docs.ethers.io/v5/)                              | Web3 client (contract testing ).                                      |
| [web3.js](https://www.npmjs.com/package/web3)                       | Web3 client (Frontend Next.js).                                       |
| [Chai](https://www.npmjs.com/package/chai)                          | javascript testing framework.                                         |
| [react-toastify](https://www.npmjs.com/package/react-toastify)      | For Notification.                                                     |   
| [hardhat](https://www.npmjs.com/package/hardhat)                    | Ethereum development environment.                                     | 
| [Redux](https://www.npmjs.com/package/hardhat)                      | For managing and centralizing application state.                      |   


----------------

# How to Execute/run the server

- Run hardhat node
    ```
    npx hardhat node || Let it run in the present terminal window & open a new terminal window
    ```
- Run test cases on the new terminal wondow
    ```
    npx hardhat test
    ```
- Deploy contract in local hardhat node to run the server
    ```
    npx hardhat run scripts/deploy.js --network localhost
    ```
- Connect hardhat with metamask
- Run Next.js frontend
    ```
    cd client
    npm run dev
    ```

# > Hardhat commands for better execution & debugging
```shell / terminal
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/deploy.js
npx hardhat help
npx hardhat run scripts/deploy.js --network <network name>
```
