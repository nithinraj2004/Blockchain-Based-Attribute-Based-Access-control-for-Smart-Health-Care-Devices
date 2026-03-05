# Setup Instructions

Follow these steps to run the project.

1. Install Kali Linux or any Linux distribution.
2. Install Node.js and npm.
3. Install Git.

Clone the Hyperledger Fabric samples repository:

git clone https://github.com/hyperledger/fabric-samples.git

Navigate to the project directory:

cd fabric-samples

Start the Fabric test network:

cd test-network
./network.sh up

Create a channel:

./network.sh createChannel

Deploy the asset-transfer-basic smart contract:

./network.sh deployCC

Navigate to chaincode folder:

cd asset-transfer-basic/chaincode-javascript

Open assetTransfer.js to view the smart contract logic.
