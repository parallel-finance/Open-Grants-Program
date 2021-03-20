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
* **Earning double interests**: users can choose to stake and lend out their tokens simultaneously based on our new approach
* **Powered by Substrate**: our platform benefits from the speed, resiliency and convenient upgradability of Polkadot

Our project utilizes substrate framework and is built on top of polkadot parachain ecosystem:
* We built the core interests model and functionalities on substrate runtime
* We enabled off-chain worker to query the current price feed of DOT and other tokens
* We will build cross-chain interoperability using XCMP protocol in the near future

Why are we building Parallel Finance?
* We decided to pick this idea because of the rising demand for decentralized lending protocols on Polkadot, as well as the lack of token liquidity that comes with staking on the mainnet. We estimate that 50% of all existing Polkadot tokens will be staked to validate the Polkadot blockchain with an estimated staking APY of 15-20%. Based on the current model, the DOT and KSM tokens will lose their liquidity once they are staked to validate the network. Institutions and large token holders have high incentives to use our platform since it will allow them to participate in staking, as well as generating additional profits through lending, and allowing them to use their DOTs as payment, or assets to trade.

### Project Details 

##### MVP links
Testnet demo: https://parallel.fi/#/

Video demo: https://youtu.be/lgQX9rELpL8

#### Mockups and UI components
![image](https://user-images.githubusercontent.com/40745291/111884834-5f719d80-8981-11eb-84cf-df6494f05650.png)
![image](https://user-images.githubusercontent.com/40745291/111884839-68626f00-8981-11eb-94ae-750dfab5e951.png)
![image](https://user-images.githubusercontent.com/40745291/111884847-6d272300-8981-11eb-9bac-81514f1f8358.png)
![image](https://user-images.githubusercontent.com/40745291/111884852-70baaa00-8981-11eb-8b42-ba6aa5045afb.png)
![image](https://user-images.githubusercontent.com/40745291/111884855-76b08b00-8981-11eb-9dc4-0a2e49845aa7.png)
![image](https://user-images.githubusercontent.com/40745291/111884857-7b753f00-8981-11eb-9197-73cd29ddb4b8.png)

##### An overview of the technology stack to be used

The lending protocol was inspired by compound protocol and our blockchain solution is developed on substrate 3.0, which allows for efficiency and scalability.
![image](https://user-images.githubusercontent.com/40745291/111884823-41a43880-8981-11eb-9c94-1a8979c6a5b8.png)

##### Lending 
##### Interest Rate Model
##### Auto Liquidation Algorthm
##### Staking Workflow

##### What your project is _not_ or will _not_ provide or implement
* Our team does not plan on implementing the support for other tokens besides the native DOT and KSM tokens and Stable Coin at the initial launch to reduce the risks in cross-collaterals
* We will not implement a decentralized exchange by ourselves. Instead, we will be focusing on building a lending/borrowing and staking protocol.

### Ecosystem Fit  

* Where and how does your project fit into the ecosystem? We are aiming to offer the first decentralized lending/borrowing and staking protocol in the Polkadot ecosystem as a DeFi and a parachain.
* Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)? Our target audience are the DOT and KSM token holders who are looking to participate in lending/borrowing, staking and unlocking liquidity for their tokens, or generating "double interests" returns by lending and staking simultaneously. This audience would include retail, institutional and large token holders, traders (arbitrage opportunities in DeFi) and network validators. In general, large token holders will have a higher incentive to join the platform earlier as the exchange rate will be more favorable.
* What need(s) does your project meet? Our project helps generate additional interests for token holders, provide assets for borrowing and unlock liquidity for token stakers who can use staked tokens (ex: xDOT) to trade, lend or use as payment.
* Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem? 
  * If so, how is your project different? Compound has been a successful and proven model for lending and borrowing assets in a decentralized manner in the Ethereum ecosystem. However, Compound doesn't offer staking services, and there is currently no decentralized lending/borrowing solution launched in the Polkadot ecosystem. Acala Network does offer staking services, but doesn't offer lending/borrowing services. From that perspective, we are a unique solution that combines both services and offers additional interests to our users.
  * If not, are there similar projects in related ecosystems? We have not yet found a project that will be focusing on generating double interests for token holders through lending and staking

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
Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting code commits made by team members in past projects. For research-related grants, references to past publications and projects in a related domain are helpful. 

If anyone on your team has applied for a grant at the Web3 Foundation previously, please list the name of the project and legal entity here.

### Team Code Repos
* https://github.com/yubo-ruan
* https://github.com/yz89
* https://github.com/GopherJ
* https://github.com/remi-gai
* https://github.com/MrPai
* https://github.com/haiyizxx

### Team LinkedIn Profiles
* https://www.linkedin.com/in/yubo-ruan/
* https://www.linkedin.com/in/remigai/

## Development Status :open_book: 

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- links to improvement proposals or [RFPs](https://github.com/w3f/General-Grants-Program/tree/master/rfp-proposal) (requests for proposal),
- academic publications relevant to the problem,
- links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
- references to conversations you might have had related to this project with anyone from the Web3 Foundation,
- previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt: 

This section should break the development roadmap down into milestones and deliverables. Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that the scope of the work can fit within a three-month period and that teams structure their roadmap as 1 milestone ≈ 1 month. 

For each milestone,

* make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
To assist you in defining it, we have created a document with examples for some grant categories [here](../src/grant_guidelines_per_category.md).
* include the amount of funding requested _per milestone_.
* include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
* provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
* commit to providing Dockerfiles for the delivery of your project. 
* indicate milestone duration as well as number of full-time employees working on each milestone, and include the approximate number of days along with the cost per day.
* _Deliverables 0a-0d are mandatory_ and shall not be removed, unless you explicitly specify a reason within the PR's `Additional Notes` section (e.g. Milestone X is research oriented and as such there is no code to test).

> :zap: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview
* **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
* **Full-Time Equivalent (FTE):**  Required workload of a full-time employee for the whole project (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent)) (e.g. 2 FTE)
* **Total Costs:** Amount of payment in USD for the whole project. The total amount of funding _needs to be below $30k for initial grants_ and $100k for follow-up grants. (e.g. 12,000 USD)

### Milestone 1 Example — Implement Cross-chain support for DOT and KSM 
* **Estimated Duration:** 8 weeks 
* **FTE:**  2
* **Costs:** 15,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. | 
| 0d. | Article/Tutorial | We will publish an article/tutorial/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.)
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be coded for the first milestone) |  
| 2. | Substrate module: Y | We will create a Substrate module that will... |  
| 3. | Substrate module: Z | We will create a Substrate module that will... |  
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  
| 5. | Docker | We will provide a dockerfile to demonstrate the full functionality of our chain |


### Milestone 2 Example — Additional features

* **Estimated Duration:** 2 month
* **FTE:**  1
* **Costs:** 4,000 USD

...


## Future Plans

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
- the team's long-term plans and intentions in relation to it.


## Additional Information :heavy_plus_sign: 

Any additional information that you think is relevant to this application that hasn't already been included.

Possible additional information to include:

* Are there are any teams who have already contributed (financially) to your project?
* Do you have a community of users or open-source developers who are contributing to your project?
