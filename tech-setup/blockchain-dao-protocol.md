# Blockchain/DAO protocol

Although the final choice has not yet been made which protocol G360DAO will be deployed and which standard DAO elements of DAO platforms will be re-used, G360DAO will stick to industry standards as much as possible.

For protocols this means that they have to be open, have a broad ecosystem of users, will have to be able to deal with smart contracts and industry SC code standard, but also be as sustainable as possible.&#x20;

They will also have to guarantee user participation in governance as much as possible and have acceptable transaction costs in case of on chain voting.&#x20;

Potential blockchain protocols that are currently being considered are EVM based blockchain protocols like Ethereum, Polygon, GnosisChain, Avalanche and Binance Smart Chain. An overview of the various options and pros and cons is shown below.



|                     | Sustainable | Transactioncosts | Transactionspeed | Interoperability | Continuity      | Decentralization |
| ------------------- | ----------- | ---------------- | ---------------- | ---------------- | --------------- | ---------------- |
|                     |             |                  |                  |                  |                 |                  |
| Ethereum            | Non-PoW     | $1+              | 30               | EVM              | Large Dev Base  | High             |
| Avalanche           | Non-PoW     | $0,25            | 4500             | EVM              | Large Dev Base  | Medium           |
| Binance Smart Chain | Non-PoW     | $0,25            | 160              | EVM              | Medium Dev Base | Medium?          |
| Polygon (Matic)     | Non-PoW     | $0,0001          | 10000+           | EVM              | Medium Dev Base | Medium           |
| Fantom              | Non-PoW     | $0,0004          | 8                | EVM              | Medium Dev Base | Medium           |
| Gnosis (xDAI)       | Non-PoW     | $0,0004          | 119              | EVM              | Large Dev Base  | Medium           |

Based on the above overview, the decision is to initially use Gnosis as the main blockchain protocol to build the DAO on. &#x20;

This choice was made because Gnosis is EVM based, so a standard ERC-20 smart contract, as well as other solidity based smart contracts can be deployed hereon.&#x20;

Furthermore, the transaction per second average is more than sufficient for the purpose of G360DAO and the transaction costs are sufficiently low to guarantee a continued participation in voting.

Although we already foresee that part of G360DAO will need to be purpose built, especially for overall bucket voting mechanisms, we anticipate to use various existing DAO governance and treasury mechanisms.&#x20;

Potential deployments of Aragon, Moloch/DAOHaus, Garden, Snapshot, Colony or DAOStack are considered for various parts or circles of the DAO.

A comparative overview is shown below.

<figure><img src="../.gitbook/assets/Comparative overview.png" alt="Comparative overview"><figcaption><p>Comparative overview</p></figcaption></figure>

Based on the comparison of the existing platform, for the launch of G360DAO, the following platforms will be used:

* Overall – until a standard solution is in the market, this smart contract will be purpose built.
* Circles – For the circles either an Aragon or a Snapshot setup will be used, depending the circle. If no sub-treasury is needed for a circle, Snapshot can have the prevalence, otherwise Aragon will be used.
