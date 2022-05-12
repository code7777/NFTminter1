# to run locally 
npx hardhat run scripts/run.js

# to redeploy 
npx hardhat run scripts/deploy.js --network rinkeby

As always when we change our contract.

    1    Redeploy.
    2   Update contract address in App.js.
    3   Update ABI file on the web app.

If you mess any of this up, you will get errors :)

# contract 
may 12 current contract address
0x9e8A527E3D34C75479f7feaDa386398E7a5EE836
may 11 
0xA0b309ab08f6e1E9CD7939531AEE493dAA640862

https://rinkeby.etherscan.io/address/0xA0b309ab08f6e1E9CD7939531AEE493dAA640862

# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```