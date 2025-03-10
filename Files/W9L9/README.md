## W8L8
### Problem statement 
*Demonstrate hardhat blockchain tutorial, URL: https://hardhat.org/tutorial*

1. Explore the tutorial section of the hardhat platform. <div align="center"> <img src="images/1.png"> </div>

2. Initialize npm into the repository and install hardhat for ethereum software development using command – npm init. <div align="center"> <img src="images/2.png"> </div> <div align="center"> <img src="images/3.png"> </div> <div align="center"> <img src="images/4.png"> </div> <div align="center"> <img src="images/5.png"> </div> <div align="center"> <img src="images/6.png"> </div> <div align="center"> <img src="images/7.png"> </div> 

3. The hardhat asks for what next we want to do. Select create an empty hardhat.config.js to proceed using command – npx hardhat init. <div align="center"> <img src="images/8.png"> </div>

4. Now download @nomicfoundation/hardhat-toolbox plugin from hardhat to develop smart contracts <div align="center"> <img src="images/9.png"> </div>

5.  Create a simple contract and compile the program.
Using command – npx hardhat compile <div align="center"> <img src="images/10.png"> </div>

6. Test the simple contract <div align="center"> <img src="images/11.png"> </div>

7. Debug with hardhat network using console.log() method in function of contract using command - npx hardhat test <div align="center"> <img src="images/12.png"> </div>

8. Deploy contract to a live network using command - npx hardhat ignition deploy ./ignition/modules/Token.js <div align="center"> <img src="images/13.png"> </div>

8. Deploying in Hardhat ignition <div align="center"> <img src="images/14.png"> </div>

9. Deploying on test network using command - npx hardhat ignition deploy ./ignition/modules/Token.js --network sepolia <div align="center"> <img src="images/15.png"> </div> <div align="center"> <img src="images/16.png"> </div>