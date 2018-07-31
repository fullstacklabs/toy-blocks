<img src="https://raw.githubusercontent.com/fullstacklabs/toy-blocks/master/FSL-logo-portrait.png" alt="FullStack Labs" align="center" />

<br />

# Toy Blocks Programming Challenge

The toy blocks programming suite includes a variety of client and API applications supporting a common toy blockchain scenario. In this simple naive blockchain each node contains a list of blocks and each block has a general data field. The API instances represent nodes in the blockchain network. Each node can be queried for status and for the list of blocks.

## Clients

For the client programming challenge you will contribute a feature to one of the client applications. Each of the client applications begins with the same functionality implemented in a different technology. Click on the appropriate repository below to access the repository for the client programming challenge.

- [React Web Client](https://github.com/fullstacklabs/toy-blocks-client-react)
- [Angular Web Client](https://github.com/fullstacklabs/toy-blocks-client-angular)
- [React Native Mobile Client](https://github.com/fullstacklabs/toy-blocks-client-react-native)

## Nodes

The following nodes are deployed for use during the client programming challenge. Each one is preloaded with a different starting blockchain.

- [Thawing Springs](https://thawing-springs-53971.herokuapp.com)
- [Secret Lowlands](https://secret-lowlands-62331.herokuapp.com)
- [Calm Anchorage](https://calm-anchorage-82141.herokuapp.com)

Each node supports the following requests that will be used in the client challenge:


### Status
```
GET /api/v1/status
```
### Blocks
```
GET /api/v1/blocks
```
