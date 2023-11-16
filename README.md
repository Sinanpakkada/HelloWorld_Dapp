steps to run this repo
1.npm init --yes
 npm install --save-dev hardhat
2.npx hardhat
3.npm install --save-dev @nomiclabs/hardhat-ethers ethers --force
4.npm install @nomiclabs/hardhat-ethers ethers hardhat @nomicfoundation/hardhat-toolbox --force
5.npm install dotenv --save --force
6 . create a .env file and type 
   PRIVATE_KEY="YOUR_PRIVATE_KEY"  
7 . replace "YOUR_PRIVATE_KEY" with your metamask private key include .env in .gitignore
8.npm install --force
9.npx hardhat compile
10.npx hardhat run scripts/deploy.js --network sepolia
11.
