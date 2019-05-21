# blockchainVoting

Install the Dependencies
 - NPM
 - $ npm install -g truffle
 - Ganache: http://truffleframework.com/ganache/
 - Metamask: https://metamask.io/
 
 Clone the project and unzip
 https://github.com/singlashashwat/blockchainVoting.git
 Unzip folder and take out all files from zip folder
 - $ cd election
 - $ npm install
 
 Start Ganache
 - Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.
 
 Compile & Deploy Election Smart Contract
 - $ truffle migrate --reset You must migrate the election smart contract each time your restart ganache.
 
 Configure Metamask
 - Unlock Metamask
 - Connect metamask to your local Etherum blockchain provided by Ganache.
 - Import an account provided by ganache.
 
 Run the Front End Application
 - $ npm run dev Visit this URL in your browser: http://localhost:3000

