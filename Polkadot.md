# Open Grant Proposal
- **Project Name:** GetCrystal
- **Team Name:** GetCrystal
- **Payment Address:** 

### Project Overview

Polkadot is a technical solution that will give game developers the opportunity to integrate NFT-related use cases into their product (app or game). For example, users will be able to change the skins of their character or open additional game locations through the purchase of NFT. On the other hand, our solution allows artists to create NFTs that will be used in games.

Our solution will be developed on Polkadot and Moonbeam and will be researched by the web application, which will allow game developers and artists to publish NFT format that is convenient for them, specifying the parameters for the NFT, the characteristics and capabilities that it will give in a game or application. NFT can not only be created, but also exchanged, sold and auctioned via a web application.

But still, the main element of the system is the API interface that our application will provide, as well as a set of libraries for the Unity 3D and Unreal Engine game engines, which will allow you to simply integrate interaction with this API into the game, to get a list of NFTs that the user owns, in order to provide the player with additional features that are associated with the possession of this NFT.

We see great potential in NFT and the growth of this market, but it seems to us that NFT as an art object has already realized itself. The time is coming for NFTs that carry some kind of use cases. It seems that the potential of NFT in games has not been realized due to the fact that integrating NFT into a game requires additional competencies that game developers often do not have. But we studied their interest in the NFT market. This is how our product was born.

We really want to implement our project on Polkadot, as we believe that the idea of parachains will help make our application adapted to high loads and a large number of requests. We also see great prospects in the entire Polkadot ecosystem. New parachains, applications appear, and we want to be part of this ecosystem.

Application usage example:

Creation of NFT collection:
https://drive.google.com/file/d/1N4o9IIcdWYV8xgZAfiiArjKa4kJllJbd/view?usp=sharing

Creation of NFT:    
https://drive.google.com/file/d/1QLLfluwWtbwudqjyu7wraQm-ixu0ljMy/view?usp=sharing

Put up for auction:
https://drive.google.com/file/d/1UVU9X4YAAld84sbFig7G75j9Jbq2p_kX/view?usp=sharing
## Project Details
Our solution is divided into three modules, each of which is necessary for the full functioning of the system, these are the modules:
1) Web application
2) API interface for the game
3) Libraries for game engines Unity 3D and Unreal engine.

### Web application

Technology: ReactJS / Solidity

0) Authorization via web3 wallet
1) NFT download
2) Loading the NFT group
3) Loading NFT with different options
4) Change NFT parameters via API
5) Create an access key to get a list of NFT account
6) Connecting a public wallet to an account
7) Generation of a unique account key

### Game API

The module that will be used for messaging between the game and the web application with NFTs connected to it.

Technology: JS / Rest API

0) Authorization by unique account key
1) Obtaining a list of NFTs owned by the user by his public key
2) Changing the characteristics of the NFT (For example, reducing the durability of the subject)

### Libraries for game engines Unity 3D and Unreal engine

This module will allow you to easily integrate interaction with a web application, and, accordingly, with NFT, in order to give game developers the opportunity to use NFT in their projects.

Technology: C# / C++

0) Authorization by unique account key
1) Getting a list of NFTs owned by the user
2) Correlation of a game object (3D model, location, skill ..) and NFT cards
3) Changing the characteristics of the NFT



![alt text](https://github.com/sapsssay/POLKADOT/blob/main/project.png?raw=true)



## Ecosystem Fit
The video game industry is attractive for development, as the number of its users is growing every year and already amounts to 3 billion people, and the total earnings of companies in this industry have exceeded 150 billion dollars a year. In the blockchain world, there are a small number of applications that allow integrating NFT into games, and they don’t have full-fledged functionality that allows trading in-game items through the blockchain comfortably and simply. Our project aims to solve this problem. Our app will position Polkadot at the intersection of the blockchain and the gaming industry. The project will attract new users from among the players to the Polkadot network, which can increase the capitalization of DOT. We will strive to integrate both indie games and serious projects with a large number of players into our platform.
## Development Roadmap
| Milestone | Description                                                                                                                                                                                        | Duration                                                                                                                                                                                         |
|-----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1         | Analytics and   connection parsing transactions Polkadot / Moonbeam                                                                                                                                | 21 days                                                                                                                                                                                          |
|           | Development   and publication of NFT and EVM smart contracts on the blockchain. Integration   of RPC methods for working with smart contracts. Connecting RPC Methods to   the Getcrystal Platform | 14   days                                                                                                                                                                                        |
|           | Connecting   a WEB3 wallet and IPFS for NFT storage                                                                                                                                                | 7   days                                                                                                                                                                                         |
|           | Create   an account and publish NFT and NFT collections                                                                                                                                            | 7   days                                                                                                                                                                                         |
|           | NFT   Placement Testing, Selling, Transferring, Buying and Auctioning                                                                                                                              | 7   days                                                                                                                                                                                         |
|           | Result                                                                                                                                                                                             | NFT   marketplace launched on Polkadot / Moonbeam with full functionality for   buying/selling/transferring/auctioning NFTs. Ready platform architecture to   continue work on the NFT GAME API. |

| Employee   Engagement             | % Engagement of   total work time | Price   |
|-----------------------------------|-----------------------------------|---------|
| Senior Frontend Developer (React) | 55%                               | $ 2706  |
| Senior Backend Developer (NodeJS) | 20,0%                             | $ 1840  |
| Blockchain Developer              | 40,0%                             | $ 3120  |
| Unity 3D Developer                | 0%                                | $ 0     |
| Unreal Engine Developer           | 0%                                | $ 0     |
| QA                                | 25%                               | $  450  |
|                                   | Total   Milestone Cost            | $  8116 |


| Milestone | Description                                                                                                                           | Duration                                                                                                                                                                                                              |         |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|
| 2         | Creation of NFT   GAME API architecture and documentation                                                                             | 14 days                                                                                                                                                                                                               |         |
|           | Development   of the NFT API, connection of methods for transmitting information about the   owner of the NFT and its characteristics | 7   days                                                                                                                                                                                                              |         |
|           | Testing   the API                                                                                                                     | 4   days                                                                                                                                                                                                              |         |
|           | Result                                                                                                                                | The   first version of NFT GAME API with the main methods of authorization and   interaction with NFT from game modules for UNITY 3D and Unreal Engine.   Documentation describing how to work with the NFT GAME API. |         |
|           | Employee   Engagement                                                                                                                 | %   Engagement of total work time                                                                                                                                                                                     | Price   |
|           | Senior   Frontend Developer (React)                                                                                                   | 35%                                                                                                                                                                                                                   | $ 1722  |
|           | Senior   Backend Developer (NodeJS)                                                                                                   | 50,0%                                                                                                                                                                                                                 | $ 4600  |
|           | Blockchain   Developer                                                                                                                | 40,0%                                                                                                                                                                                                                 | $ 3120  |
|           | Unity   3D Developer                                                                                                                  | 70,0%                                                                                                                                                                                                                 | $ 1820  |
|           | Unreal   Engine Developer                                                                                                             | 70,0%                                                                                                                                                                                                                 | $ 2030  |
|           | QA                                                                                                                                    | 25%                                                                                                                                                                                                                   | $ 450   |
|           |                                                                                                                                       | Total   Milestone Cost                                                                                                                                                                                                | $ 13742 |



| Milestone | Description                                                                              | Duration                                                                                                                                                                                                                                         |        |
|-----------|------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| 3         | Creation of   architecture and documentation for game modules UNITY 3D and Unreal engine | 10 days                                                                                                                                                                                                                                          |        |
|           | Development   of the NFT GAME API connection module for UNITY 3D                         | 14   days                                                                                                                                                                                                                                        |        |
|           | Development   of the NFT GAME API module for Unreal engine                               | 14   days                                                                                                                                                                                                                                        |        |
|           | Binding   NFT GAME API and modules for Unity 3D and Unreal engine                        | 5   days                                                                                                                                                                                                                                         |        |
|           | Testing   the operation of the NFT GAME API and modules for game engines                 | 4   days                                                                                                                                                                                                                                         |        |
|           | Result                                                                                   | Ready-made   modules for the UNITY 3D and Unreal engine game engines that developers can   use to interact with the NFT GAME API. Documentation describing how to work   with NFT GAME API plug-ins for Unity 3D and Unreal Engine game engines. |        |
|           | Employee   Engagement                                                                    | %   Engagement of total work time                                                                                                                                                                                                                | Price  |
|           | Senior   Frontend Developer (React)                                                      | 10,0%                                                                                                                                                                                                                                            | $ 492  |
|           | Senior   Backend Developer (NodeJS)                                                      | 10,0%                                                                                                                                                                                                                                            | $ 920  |
|           | Blockchain   Developer                                                                   | 10,0%                                                                                                                                                                                                                                            | $ 780  |
|           | Unity   3D Developer                                                                     | 0%                                                                                                                                                                                                                                               | $ 0    |
|           | Unreal   Engine Developer                                                                | 0%                                                                                                                                                                                                                                               | $ 0    |
|           | QA                                                                                       | 25%                                                                                                                                                                                                                                              | $ 450  |
|           |                                                                                          | Total   Milestone Cost                                                                                                                                                                                                                           | $ 2642 |


| Milestone | Description                                                                                | Duration                                                                                                                                                                                                                                                                                                        |        |
|-----------|--------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| 4         | Development of   a DEMO game using the NFT GAME API                                        | 21 days                                                                                                                                                                                                                                                                                                         |        |
|           | NFT   GAME API connection                                                                  | 3   days                                                                                                                                                                                                                                                                                                        |        |
|           | Connecting   the Unity 3D module                                                           | 4   days                                                                                                                                                                                                                                                                                                        |        |
|           | Testing   the game, writing documentation and an example of using the developed   solution | 7   days                                                                                                                                                                                                                                                                                                        |        |
|           | Result                                                                                     | The   developed DEMO game, which uses the game module and the NFT GAME API,   demonstrates all the possibilities of working with NFT that will be available   to game developers. Documentation describing the process of connecting   modules for Unity 3D and Unreal engine game engines to the NFT GAME API. |        |
|           | Employee   Engagement                                                                      | %   Engagement of total work time                                                                                                                                                                                                                                                                               | Price  |
|           | Senior   Frontend Developer (React)                                                        | 0%                                                                                                                                                                                                                                                                                                              | $ 0    |
|           | Senior   Backend Developer (NodeJS)                                                        | 20,0%                                                                                                                                                                                                                                                                                                           | $ 1840 |
|           | Blockchain   Developer                                                                     | 10,0%                                                                                                                                                                                                                                                                                                           | $ 780  |
|           | Unity   3D Developer                                                                       | 30,0%                                                                                                                                                                                                                                                                                                           | $ 780  |
|           | Unreal   Engine Developer                                                                  | 30,0%                                                                                                                                                                                                                                                                                                           | $ 870  |
|           | QA                                                                                         | 25%                                                                                                                                                                                                                                                                                                             | $ 450  |
|           |                                                                                            | Total   Milestone Cost                                                                                                                                                                                                                                                                                          | $ 4720 |


| Project   team                      | Engagement   (months) | Rate per   month |
|-------------------------------------|-----------------------|------------------|
| Senior   Frontend Developer (React) | 1,2                   | $ 4100,00        |
| Senior   Backend Developer (NodeJS) | 2                     | $ 4600,00        |
| Blockchain   Developer              | 1,5                   | $ 5200,00        |
| Unity 3D   Developer                | 1                     | $ 2600,00        |
| Unreal   Engine Developer           | 1                     | $ 2900,00        |
| QA                                  | 1                     | $ 1800,00        |
|                                     | Total                 | $ 29220,00       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     
