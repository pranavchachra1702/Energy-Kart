# Energy-Kart: A Peer to Peer Energy Trading application using Blockchain
One area of focus in the exploration of Blockchain technology is the development of a Decentralized Energy network. This concept originates from a local marketplace integrated with a microgrid, where specific Prosumers generate energy via sources such as solar panels, and can distribute surplus energy to Consumers in need. Transactions are executed using coins stored in each Resident's account, following predefined contracts and rates, with coins debited from the Consumer and credited to the Producer within a designated timeframe.
<br><br>
This code pattern illustrates such an application on an Ethereum Blockchain. The network comprises Prosumers and Consumers who can exchange coins for energy between themselves. Each transaction must be atomic and recorded on the Blockchain for transparency and validation. Furthermore, the network can be expanded to involve Retailers for coin exchange into other currencies and incorporate various green-energy companies to facilitate energy transactions within the network.
<br><br>
###  Architecture Advantages
* Facilitates a Peer-to-Peer Network
*	Enhances Grid Network balance by enabling energy exchange between producers and consumers
*	Achieves consensus without centralization
*Enables real-time Measurement, Verification, and Settlement of traded energy
<br><br>

###  Why Ethereum
* Most stable Blockchain Platform
* Proof of Work Algorithm for block mining doesn't require an ASIC
* Offers Application Programming Interface (API) for Decentralized Applications (DApp) Development
* Supports approximately 15 Transactions per second
*	Block Time: 10-19 seconds
<br><br>

### Features
The Energy Marketplace has the following features:
* Sell : 
  - This option enables any user having surplus energy to broadcast tokens, account address (public key) and the start bid to be broadcasted on the network.
* Buy : 
  - This option enables any user who needs to purchase energy to enter his account address (public key) and make a bid. 
  - Multiple users can bid and only the highest bid is taken into account after a predefined timeout.
* Close Connection :
  - This option enables the buyer to stop drawing power from the batteries once the buyer’s requirement is fulfilled.
  <br><br>

After a timestep, the latest bid value along with buyer’s and seller’s address are fed into the Blockchain using the Smart Contract.
Corresponding crypto-currency (Ether) are sent from the buyer’s account to the seller’s account for every KWH power consumed by the buyer.
 
