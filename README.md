![10 Academy](https://static.wixstatic.com/media/081e5b_5553803fdeec4cbb817ed4e85e1899b2~mv2.png/v1/fill/w_246,h_106,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/10%20Academy%20FA-02%20-%20transparent%20background%20-%20cropped.png)
# Algorand
Algorand is a blockchain-based platform designed to deliver trustless and secure transactions at high speeds. It seeks to enable the everyday user to securely and conveniently access decentralized applications and services. With a wide range of features, Algorand has quickly become popular among developers and users alike. 


The Algorand project provides its users with a powerful suite of tools to build, test and deploy decentralized applications. Its user friendly interface also makes it easy for people of all levels of technical knowledge to quickly pick up and start using the platform. Here are some of the features provided by Algorand: 

* High Performance: Algorand provides low latency and high throughput, making it suitable for a wide variety of decentralized applications.
* Decentralized Consensus: Algorand utilizes a decentralized consensus algorithm, allowing nodes to remain in agreement on the state of the network.
* Secure Data Storage: The network stores data in an encrypted format, ensuring that no malicious actors can access sensitive user data.
* Smart Contracts: The platform supports smart contract execution, allowing developers to easily create complex applications with ease.
* Interoperability: Algorand is designed to be interoperable with other protocols and platforms, allowing users to easily move their funds between different networks. 


I recommend the following steps when beginning with Algorand: 

1. Familiarize yourself with the Algorand Documentation. This includes learning about the consensus algorithm and familiarizing yourself with specific commands used on the platform.
2. Sign up for an Algorand Wallet. This will allow you to securely store your funds and interact with decentralized applications on the network. 
3. Connect to an Algorand node. This connection allows you to easily access data from the blockchain, such as transactions and blocks. 
4. Create and deploy an Algorand Smart Contract. This allows you to easily create complex logic which can be securely executed on the network.
5. Learn about Algorand’s advanced features, such as atomic transfers, asset transfers and transaction permissions. 

## Folder Structure
### You will find the following directories in this project
1. `api` - consists scripts for a FastAPI development
2. `images` - contains screenshots of the frontend app
3. `NFT_js` - Create an asset, transfer an asset, and opt-in implementation using JS SDK
4. `NFT_py` - Create an asset, transfer an asset, and opt-in implementation using Python SDK
5. `notebooks` - here your will find two files: algo_starter and asset notebooks. These files will try to show the basic implementations of algoSDK.
6. `react` - Lastly, you will find the frontend react app in this directory.
__________

## Installation
Before installing this app, you need to prepare a few things
- install node.js
- prepare a `config.py` file in the api folder

your config file should look like this

```bash
# create pinata api account and input the following
API_KEY = "your api key"
API_SECRET ="your api secret key"
# generate app email password from your gmail
EPASS= "your generated app password"
```

```bash
git clone https://github.com/Nathnael12/web3_certificate_generation_verification.git

cd web3_certificate_generation_verification

# start api
cd api
uvicorn app:app --reload

# start react frontend
# go to the react folder first 
# from the api folder . . . .
cd ../react
npm run start



```
# Acknowledgement / Source


[1]  https://github.com/Nathnael12/web3_certificate_generation_verification 👌🏽
