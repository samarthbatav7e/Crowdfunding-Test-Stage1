# Crowdfunding WebApp Test Stage1

# Deployed Features for Stage 1 Testing->
- > User can start a fundraising.
- > Anyone in the network can contribute.
- > Project ends if the target contribution amount is reached.
- > Project expires if targeted amount is not fulfilled till deadline.
- > Contributors can withdraw contributed amount if project expires.
- > Connect with wallet.



----------------

# How to Execute/run the server

- Run hardhat node ->
    npx hardhat node || Let it run in the present terminal window & open a new terminal window
    ---
- Run test cases on the new terminal wondow->

    npx hardhat test
    ```
- Deploy contract in local hardhat node to run the server->
    ```
    npx hardhat run scripts/deploy.js --network localhost
    ```
- Connect hardhat with metamask (By adding the metamask extension to the browser (in our case Chrome) & creating the account)

- Run Next.js frontend->
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
