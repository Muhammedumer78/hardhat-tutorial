#SETTING UP THE HARDHAT ENVIRONMENT

We'll install Hardhat using the Node.js package manager (npm), which is both a package manager and an online repository
for JavaScript code.

1.Creating a new directory:
mkdir hardhat-tutorial

2.Switch to directory
cd hardhat-tutorial

3.If you don't have node package manager(npm)then install it by,otherwise jump to step 4:

<!-- (for npm7+ and npm6) -->
//npm init

<!-- (for yarn) -->
//yarn init

4.Install Hardhat by:

<!-- (for npm7 + and npm6) -->
//npm install --save-dev hardhat 

<!-- (for yarn) -->
//yarn add --dev hardhat 

5.run hardhat:
//npx hardhat

6.Select hardhat.config.js on shown options by terminal or CMD(such a scene will create on your terminal or CMD):

$ npx hardhat
888    888                      888 888               888
888    888                      888 888               888
888    888                      888 888               888
8888888888  8888b.  888d888 .d88888 88888b.   8888b.  888888
888    888     "88b 888P"  d88" 888 888 "88b     "88b 888
888    888 .d888888 888    888  888 888  888 .d888888 888
888    888 888  888 888    Y88b 888 888  888 888  888 Y88b.
888    888 "Y888888 888     "Y88888 888  888 "Y888888  "Y888

👷 Welcome to Hardhat v2.9.9 👷‍

? What do you want to do? …
  Create a JavaScript project
  Create a TypeScript project
❯ Create an empty hardhat.config.js
  Quit

7.Install recommended plugin by hardhat(@nomicfoundation/hardhat-toolbox) by:

% (for npm7+)
//npm install --save-dev @nomicfoundation/hardhat-toolbox

% (for npm6)
//npm install --save-dev @nomicfoundation/hardhat-toolbox @nomicfoundation/hardhat-network-helpers @nomicfoundation/hardhat-chai-matchers @nomiclabs/hardhat-ethers @nomiclabs/hardhat-etherscan chai ethers hardhat-gas-reporter solidity-coverage @typechain/hardhat typechain @typechain/ethers-v5 @ethersproject/abi @ethersproject/providers

% (for yarn)
//yarn add --dev @nomicfoundation/hardhat-toolbox @nomicfoundation/hardhat-network-helpers @nomicfoundation/hardhat-chai-matchers @nomiclabs/hardhat-ethers @nomiclabs/hardhat-etherscan chai ethers hardhat-gas-reporter solidity-coverage @typechain/hardhat typechain @typechain/ethers-v5 @ethersproject/abi @ethersproject/providers

% THIS IS THE WHOLE SETUP FOR HARDHAT ENVIRONMENT.....................................