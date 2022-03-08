# EGF Grants Program

### Table of Contents:

1. [Overview](./#overview): how to address the issue of decentralization and achieve quorum if company validators do not vote (to maintain neutrality).
2. [Process](./#process): The entire process of proposals, including [guidelines](applications/application-template.md), interviews, onboarding and how funds will be disbursed.
3. [Tiers](./#tiered-amounts): different tiered amounts, benefits and requirements
4. [Categories](./#categories-non-exhaustive-list): Identify categories proposal belongs to
5. [Application template](applications/application-template.md):
   1. [Project Overview](applications/application-template.md#overview)
   2. [Project Description](applications/application-template.md#project-description)
   3. [Team Profile](applications/application-template.md#team-profile)
   4. [Ecosystem fit/impact](applications/application-template.md#ecosystem-fit-impact)
   5. [Development status](applications/application-template.md#development-status)
   6. [Development roadmap](applications/application-template.md#development-roadmap)
   7. [Future plans](applications/application-template.md#future-plans)

### Overview

All proposals are to be **voted on-chain**. Prior to on-chain voting, it is paramount that the proposer follows the following set of guidelines to ensure a greater chance that their proposal will be passed.

These guidelines are written in order to:

1. Propose best practices for drafting a proposal
2. Address the issue of reaching quorum for the reasons stated below:
   1. public validators not controlling enough FX currently, and
   2. Internal and institutional validators are not voting to maintain neutrality
3. Allow for the FunctionX team to indirectly exercise their voting power (uniquely from a delegator’s standpoint, and not from a validator’s standpoint) with full knowledge that the proposal was reviewed preliminarily by skilled individuals

In that perspective, each proposal shall lead to:

1. The designation of 3 team developers, for each proposal that reaches out to the committee: The internal developers are chosen based on their skillset; hence, a market-making proposal will be judged by traders/trading system engineers, while a say - NFT proposal will be judged by a smart contract developer.
2. The assignment: Team will designate voting power to each committee member such that each committee member will control each one of the team's top 3 validators.
3. Each committee member acts independently.

Funding:
1. Formal proposals should have the breakdown of all milestones and requested funds for each milestone.
2. Only funds for each milestone can be requested at any given time.
   1. For eg. if your project has the following specs: Milestone 1 ($3,000) & Milestone 2 ($4,000).
   2. The submission of your EGF proposal (on-chain) should only request for $3,000.
   3. Once you have completed Milestone 1, then you may submit another EGF proposal (on-chain) for $4,000.

{% hint style="info" %}
The rest of the voting power would then come from the public delegators and validators.
{% endhint %}

### Process

Before setting up any proposal on-chain, it is strongly recommended to any proposer to proceed the following way:

1. Contact the team with an inquiry form
   1. The proposer must contact the Function X team by correctly filling in the [inquiry-application-template](applications/inquiry\_proposal\_applicants/inquiry-application-template.md) which is points 1-5 (inclusive) of the EGF proposal form
      1. [Fork](https://github.com/FunctionX/FunctionX-EGF/fork) this repository
      2. In the newly created fork, create a copy of the [inquiry-application-template](applications/inquiry\_proposal\_applicants/inquiry-application-template.md). If you're using the GitHub web interface, you will need to create a new file and copy the [contents](https://raw.githubusercontent.com/FunctionX/FunctionX-EGF/main/applications/inquiry\_proposal\_applicants/inquiry-application-template.md) of the template inside the new one. Make sure you **do not modify the template file directly**.
      3. Name the new file after your project: `project_name.md`.
      4. Fill out the template with the details of your project. The more information you provide, the faster the review.
      5. Once you're done, create a pull request. The pull request should only contain _one new file_—the Markdown file you created from the template.
   2. The more information provided, the better guidance the team will be able to provide to the proposer.
2. Identify support opportunities
   1. Identify ways to help, beyond monetary support e.g. coding, interfaces, source code, etc.
   2. Request more information in the Inquiry Form
3. Formal proposal
   1. If identified as requiring financial support
   2. [Fork](https://github.com/FunctionX/FunctionX-EGF/fork) this repository
   3. In the newly created fork, create a copy of the [formal-application-template](applications/formal\_proposal\_applicants/formal-application-template.md). If you're using the GitHub web interface, you will need to create a new file and copy the [contents](https://raw.githubusercontent.com/FunctionX/FunctionX-EGF/main/applications/formal\_proposal\_applicants/formal-application-template.md) of the template inside the new one. Make sure you **do not modify the template file directly**.
   4. Name the new file after your project: `project_name.md`.
   5. Fill out the template with the details of your project. The more information you provide, the faster the review.
   6. Once you're done, create a pull request. The pull request should only contain _one new file_—the Markdown file you created from the template.
4. Evaluation
   1. Provide feedback
   2. May request for more information
5. Technical interviews
   1. If required, depending on the [tier](./#tiered-amounts) requested, technical interviews will be scheduled
6. Funding decision
7. Onboarding
   1. We’ll write up a contract and do KYC before disbursing funds
   2. Funds will be disbursed according to [milestones](egf-proposal-form.md#development-roadmap). This means you can only request for funds for the milestone you are working on currently. 

### Tiered amounts

{% hint style="info" %}
**The amounts are in USD. The grants will be paid out in FX, the amount will be calculated based on the exchange rate on** [**CoinMarketCap**](https://coinmarketcap.com) **at the time of payment.**
{% endhint %}

| **Levels**         | **1 (FaXt Grants)**                                                                                                 | **2 (FaXt Grants)**       | **3**                                      | **4**                                                                                     |
| ------------------ | ------------------------------------------------------------------------------------------------------------------- | ------------------------- | ------------------------------------------ | ----------------------------------------------------------------------------------------- |
| **Amount (Up to)** | $5,000                                                                                                              | $10,000                   | $50,000                                    | $100,000 & Above                                                                          |
| **Target**         | Individuals                                                                                                         | Individuals & small teams | Small teams/start-ups                      | Companies/foundations with a proven track record (would require pitch calls & interviews) |
| **Benefits**       | <ol><li>Feedback during application process and evaluation</li><li>Introduction to related teams/projects</li></ol> | All of the previous       | All of the previous + grants program badge | All of the previous + further collaboration like co-branding/marketing…                   |

### Categories (non-exhaustive list)

{% hint style="info" %}
It is paramount that you have categorized your project for us to easily identify the team to evaluate your project.
{% endhint %}

1. Blockchain Network layer
   1. Tooling – Improving the developer experience
   2. Documentation
2. On-chain Apps
   1. DeFi
      1. Loaning and borrowing
      2. Automated Market Makers (AMM)
      3. Decentralised Exchanges (DEX)
      4. Insurance
   2. NFT marketplace
   3. Games
   4. Property
   5. Social
3. Off-chain apps
   1. Data Analysis
      1. Data visualization tools
      2. Report generation
   2. Wallets
   3. General apps (Web, Android, IOS…)
4. Trading
   1. Market making bot
   2. Trading systems
