# Parallel Finance Open Grant Proposal

* **Project Name:** Parallel Finance
* **Team Name:** Parallel
* **Payment Address:** 0x17816E9A858b161c3E37016D139cf618056CaCD4

## Project Overview :page_facing_up: 

Parallel finance is a decentralized lending/borrowing and staking protocol built on top of the Polkadot ecosystem. Our platform will allow users to earn "double interests" from staking and lending their tokens simultaneously (hence the name "parallel" finance).

### Overview

Our platform offers a few key features and benefits:
* **Lending and borrowing**: users can lend and borrow assets based on interest rates.
* **Staking**: users can participate in Polkadot’s network validation and earn rewards. 
* **Earning double interests**: users can choose to stake and lend out their tokens simultaneously based on our new approach.
* **Powered by Substrate**: our platform benefits from the speed, resiliency and convenient upgradability of Polkadot.

Our project utilizes substrate framework and is built on top of polkadot parachain ecosystem:
* We built the core interests model and functionalities on substrate runtime
* We enabled off-chain worker to query the current price feed of DOT and other tokens
* We will build cross-chain interoperability using XCMP protocol in the near future

**Why are we building Parallel Finance?**
* We decided to pick this idea because of the rising demand for decentralized lending protocols on Polkadot and Kusama, as well as the lack of token liquidity that comes with staking on the mainnet. We estimate that 50% of all existing DOT and KSM tokens will be staked for blockchain validation with an estimated staking APY of 10-20%. However, the DOT and KSM tokens will lose their liquidity once they are staked to validate the network. Institutions and large token holders have high incentives to use our platform since it will allow them to not only participate in staking, but also generate additional profits through lending, and allow them to use their DOTs and KSMs as payment, or trading assets.

### Project Details 

##### MVP links
* Testnet demo: https://parallel.fi/#/
* Video demo: https://youtu.be/lgQX9rELpL8

#### Mockups and UI components
![image](https://user-images.githubusercontent.com/40745291/111884834-5f719d80-8981-11eb-84cf-df6494f05650.png)
![image](https://user-images.githubusercontent.com/40745291/111884839-68626f00-8981-11eb-94ae-750dfab5e951.png)
![image](https://user-images.githubusercontent.com/40745291/111884847-6d272300-8981-11eb-9bac-81514f1f8358.png)
![image](https://user-images.githubusercontent.com/40745291/111884852-70baaa00-8981-11eb-8b42-ba6aa5045afb.png)
![image](https://user-images.githubusercontent.com/40745291/111884855-76b08b00-8981-11eb-9dc4-0a2e49845aa7.png)
![image](https://user-images.githubusercontent.com/40745291/111884857-7b753f00-8981-11eb-9197-73cd29ddb4b8.png)

##### An overview of the technology stack to be used

The lending protocol was inspired by compound protocol and our blockchain solution is developed on substrate 3.0, which allows for efficiency and scalability.

##### Lending and Borrowing Workflow
![image](https://user-images.githubusercontent.com/56744348/111891853-0aa34680-89c4-11eb-8657-7396d1ab154d.png)
##### Interest Rate Model
![image](https://user-images.githubusercontent.com/56744348/111891848-070fbf80-89c4-11eb-8d15-c3ee5fcb7cf3.png)
##### Auto Liquidation Algorithm
![image](https://user-images.githubusercontent.com/56744348/111891839-f19a9580-89c3-11eb-9c08-2094e1aa5972.png)
##### Staking Workflow
![image](https://user-images.githubusercontent.com/56744348/111891844-ff501b00-89c3-11eb-829d-130d6bb48e67.png)
##### Staking Rate Model
![image](https://user-images.githubusercontent.com/56744348/111891842-f8c1a380-89c3-11eb-9210-1bf0bbd9ed83.png)

##### What your project is _not_ or will _not_ provide or implement
* Our team does not plan on implementing the support for other tokens besides the native DOT and KSM tokens and Stable Coin at the initial launch in order to reduce the risks in cross-collaterals
* We will not implement a decentralized exchange by ourselves. Instead, we will be focusing on building the lending/borrowing and staking protocol.

### Ecosystem Fit  

* **Where and how does your project fit into the ecosystem?** We are aiming to offer the first decentralized lending/borrowing and staking protocol in the Polkadot and Kusama ecosystem as a DeFi and a parachain.
* **Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?** Our target audience are the DOT and KSM token holders who are looking to participate in lending/borrowing, staking and unlocking liquidity for their staked tokens, or generating "double interests" returns by lending and staking simultaneously. This audience would include retail, institutional and large token holders, traders (arbitrage opportunities in DeFi) and network validators. In general, large token holders will have a higher incentive to join the platform earlier as the exchange rate will be more favorable.
* **What need(s) does your project meet?** Our project helps generate additional interests for token holders, provide assets for borrowing and unlock liquidity for token stakers who can use staked tokens (ex: xDOT) to trade, lend or use as payment.
* **Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?** 
  * **If so, how is your project different?** Compound has been a successful and proven model for lending and borrowing assets in a decentralized manner in the Ethereum ecosystem. However, Compound doesn't offer staking services, and there is currently no decentralized lending/borrowing solution launched in the Polkadot ecosystem. Acala Network does offer staking services, but doesn't offer lending/borrowing services. From that perspective, we are a unique solution that combines both services and offers additional interests to our users.
  * **If not, are there similar projects in related ecosystems?** We have not yet found a project that will be focusing on generating double interests for token holders through lending and staking.

## Team :busts_in_silhouette:

### Team members
* Name of team leader: Yubo Ruan
* Names of team members: 	Remi Gai, Zhou Yang, Li Pai, Cheng Jiang, Hai Yi

### Contact
* **Contact Name:** Yubo Ruan 
* **Contact Email:** yubo@parallel.fi
* **Website:**
* www.parallel.fi

### Legal Structure 
(we are in the process of register the legal entity)
* **Registered Address:** N/A 
* **Registered Legal Entity:** N/A


### Team's experience
* Yubo Ruan:
* Zhou Yang:
* **Remi Gai**: Remi is a software engineer with a background in product management, entrepreneurship and venture capital, and currently works at Microsoft. Previously, Remi worked as an early stage investor at 8 Decimal Capital, a crypto/blockchain focused fund, and was the co-founder and Product Lead of a blockchain development firm, Bitsystems, based in Cambridge, Massachusetts.
* Li Pai:
* Cheng Jiang:
* Hai Yi:

Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting code commits made by team members in past projects. For research-related grants, references to past publications and projects in a related domain are helpful. 
If anyone on your team has applied for a grant at the Web3 Foundation previously, please list the name of the project and legal entity here.

### Team Code Repos
* Backend: https://github.com/parallel-finance/hackathon-2021-spring/tree/main/teams/22-Parallel/src/parallel
* Frontend: https://github.com/parallel-finance/hackathon-2021-spring/tree/main/teams/22-Parallel/src/parallel-dapp

### Team LinkedIn Profiles
* https://www.linkedin.com/in/yubo-ruan/
* https://www.linkedin.com/in/remigai/

## Development Roadmap :nut_and_bolt: 

### Overview

### Milestone 1 — Implement Cross-chain support for DOT and KSM 
* **Estimated Duration:** 8 weeks 
* **FTE:**  2
* **Costs:** 8.333 ETH (15,000 USD at $1,802/ETH)

The major deliverable of for this milestone:
* Develop cross-chain capabilities between DOT and KSM tokens
* Users will be able to deposit DOT tokens as collateral and borrow KSM tokens through our web app

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0 | License | Apache 2.0 / MIT / Unlicense |
| 1.a | Substrate module: DOT | We will create a Substrate module that will..... enable some kind of cross-chain feature with DOT|  
| 1.b | Testing and Documentation | While we develop our module, we will ensure that our code has significant test coverage (>80%) to ensure quality and provide explanations on how the functions work for the community to review, as well as craft test guides|  
| 2.a | Substrate module: KSM | We will create a Substrate module that will..... enable some kind of cross-chain feature with KSM|  
| 2.b | Testing and Documentation | While we develop our module, we will ensure that our code has significant test coverage (>80%) to ensure quality and provide explanations on how the functions work for the community to review, as well as craft test guides|  
| 3.a | Integration with front-end | We will integrate our existing front end to the finalized substrate backend |  
| 3.b | Article/Tutorial | We will create an article and a video demo that explains how users can start using the platform in lending and borrowing for DOT and KSM |  
|3.c | Docker | We will provide a dockerfile to demonstrate the full cross-chain functionality | 
| 4. | User Testing | We will conduct user testing to improve our product's UX and UI, to ensure that the borrowing and lending functionalities are intuitive  |  

### Milestone 2 — Enable Staking for DOT

* **Estimated Duration:** 8 weeks 
* **FTE:**  2
* **Costs:** 8.333 ETH (15,000 USD at $1,802/ETH)

The major deliverable of for this milestone:
* Implement the modules that allow for staking functionality, which includes
  * Exchange Rate
  * 28 days locking period for unstaking tokens
  * Slashing scenarios
  * Relay tokens to validators
* Users will be able to stake DOT tokens, and receives xDOT in return. xDOT will then start accruing interests from staking and also be used for lending or transfered elsewhere for payment or trading.

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0 | License | Apache 2.0 / MIT / Unlicense |
| 1.a | Substrate module: Staking DOT | We will create a Substrate module that will..... |  
| 1.b | Substrate module: Unstaking DOT | We will implement a 28 days locking period for the unstaking process of DOT tokens from validators|  
| 1.c | Substrate module: Exchange Rate | We will implement a the process for issuing and trading DOT for xDOT with the users based on our exchange rate|  
| 1.d | Substrate module: Slashing Scenario  | Staking tokens does have inherent risks of being slashed. We will implement our model that will change the exchange rate in case of slashing scenarios|  
| 1.e | Testing and Documentation | While we develop our module, we will ensure that our code has significant test coverage (>80%) to ensure quality and provide explanations on how the functions work for the community to review, as well as craft test guides|  
| 2.a | Substrate module: KSM | Since DOT and KSM will have similar code, we will mainly transfer over some of the previous development to allow for KSM staking|  
| 2b| Testing and Documentation | While we develop our module, we will ensure that our code has significant test coverage (>80%) to ensure quality and provide explanations on how the functions work for the community to review, as well as craft test guides|  
| 3.a | Integration with front-end | We will integrate our existing front end to the finalized substrate backend |  
| 3.b | Article/Tutorial | We will create an article and a video demo that explains how users can start using the platform for staking for DOT and KSM. Additionally, we will also create tutorials to walk show the users how they can earn "double interests" through staking and lending at the same time via xDOT and xKSM |  
|3.c | Docker | We will provide a dockerfile to demonstrate the end-to-end use case of Staking/Unstaking DOT and KSM tokens  | 
| 4. | User Testing | We will conduct user testing to improve our product's UX and UI, to ensure that the staking functionalities are intuitive  |   

## Future Plans

**Community Development**:
- In the short term, we will focus a lot of our energy in acquiring early users for our platform, who are large token holders and institutions. The exchange rate will be lower initially as the pool size and number of blocks are lower, so there's a strong incentive for larger players to join early. In addition, as the Kusama and Polkadot mainnets are approaching, we will be forming partnership with validators who might be interested in forming partnerships or use our platform to gain liquidity on their staked tokens.
- We will also be posting on social media (Twitter, Medium, Youtube) to provide video tutorials regarding our platform and work with influencers, who can provide clear guidance to the mainstream users on how to use our platform.
- Our long term plan is to provide a suite of products that will allow users to earn additional interests for their assets on our Defi, as we truly believe in the benefits of decentralization and allowing the more mainstream investors to participate in the financial economy.

**Product Development**:
* This is our tentative development roadmap for the rest of this year:
![image](https://user-images.githubusercontent.com/56744348/111891918-94ebaa80-89c4-11eb-8707-a16b33e7b54c.png)


## Additional Information :heavy_plus_sign: 

* We are a team that met and formed during the March 2021 Polkadot Hackathon in Shanghai. Our team members are both in the US and China, and come from a background in engineering (crypto/blockchain, traditional tech company), product management and financial background (venture capital, Defi). We were able to deliver our proof of concept at a really quick pace, earning third spot at the Hackathon.

* We are currently still in the process of creating our white paper, but you can find more details about our platform on our gitbook: https://docs.parallel.fi/.

* Email: team@parallel.fi
* Website: parallel.fi
* Twitter: https://twitter.com/ParallelFi
* Unofficial white paper: https://docs.parallel.fi/
* Testnet demo: https://parallel.fi/#/app
* Video demo (Hackathon March 2021): https://youtu.be/lgQX9rELpL8
