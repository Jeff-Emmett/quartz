---
title: |
	| **Conviction Voting**
subtitle: |
	| A Dynamic Approach to Collective Decision Making in Decentralized Organizations
date: \today
author: |
  | Jeff Emmett
abstract: |
	Conviction voting is a novel decision-making mechanism that aims to improve governance in decentralized organizations. By incorporating aspects of time and commitment, it seeks to overcome shortcomings found in traditional voting methods. This whitepaper will provide an overview of conviction voting, explain how it functions, and explore its advantages compared to other voting systems.
numbersections: true
secnumdepth: 2
geometry: "margin=4cm, a4paper"
bibliography: /Users/orion/Desktop/lit.bib
link-citations: true
---

# Conviction Voting: A Dynamic Approach to Collective Decision Making

## Table of Contents

1.  [Introduction](https://chat.openai.com/?model=gpt-4#introduction)
2.  [Background](https://chat.openai.com/?model=gpt-4#background)
    -   [Quadratic Voting](https://chat.openai.com/?model=gpt-4#quadratic-voting)
    -   [Token Curated Registries](https://chat.openai.com/?model=gpt-4#token-curated-registries)
3.  [Conviction Voting](https://chat.openai.com/?model=gpt-4#conviction-voting)
    -   [Concept](https://chat.openai.com/?model=gpt-4#concept)
    -   [Algorithm](https://chat.openai.com/?model=gpt-4#algorithm)
4.  [Advantages of Conviction Voting](https://chat.openai.com/?model=gpt-4#advantages)
5.  [Case Studies](https://chat.openai.com/?model=gpt-4#case-studies)
6.  [Conclusion](https://chat.openai.com/?model=gpt-4#conclusion)

## 1. Introduction <a name="introduction"></a>

Conviction voting is a novel decision-making mechanism that aims to improve governance in decentralized organizations. By incorporating aspects of time and commitment, it seeks to overcome shortcomings found in traditional voting methods. This whitepaper will provide an overview of conviction voting, explain how it functions, and explore its advantages compared to other voting systems.

## 2. Background <a name="background"></a>

### 2.1 Quadratic Voting <a name="quadratic-voting"></a>

Quadratic voting is a mechanism that allows participants to express the intensity of their preferences. It assigns a cost to each additional vote, making it increasingly expensive to vote in favor of or against a proposal. While it enables the consideration of minority preferences, it is still prone to manipulation and does not account for long-term commitment to decisions.

### 2.2 Token Curated Registries <a name="token-curated-registries"></a>

Token curated registries (TCRs) are decentralized, token-weighted lists that use economic incentives to curate high-quality content. While TCRs offer some improvements to decision-making processes, they tend to prioritize short-term gains over long-term vision, leading to suboptimal outcomes.

## 3. Conviction Voting <a name="conviction-voting"></a>

### 3.1 Concept <a name="concept"></a>

Conviction voting introduces the concept of "conviction" as a measure of both the amount of support and the duration of commitment to a particular proposal. This system aims to prioritize proposals that have sustained support over time, rewarding long-term commitment and reducing the influence of short-term speculation.

### 3.2 Algorithm <a name="algorithm"></a>

The conviction voting algorithm calculates conviction scores for each proposal using the following formula:

`conviction = (staked_tokens * (1 - (1 - α)^time_held))^γ`

Where:

-   `staked_tokens`: The amount of tokens staked in support of the proposal.
-   `α`: A constant decay factor (0 < α < 1) that influences the rate at which conviction accumulates.
-   `time_held`: The duration for which tokens have been staked on the proposal.
-   `γ`: A constant that determines the non-linear relationship between staked tokens and conviction.

The proposal with the highest conviction score is deemed the most favorable and gets prioritized for implementation.

## 4. Advantages of Conviction Voting <a name="advantages"></a>

1.  **Long-term Commitment**: Conviction voting rewards long-term commitment to proposals, ensuring that participants are genuinely invested in the outcome of decisions.
2.  **Reduced Speculation**: The influence of short-term speculation is minimized, promoting more stable and well-thought-out decisions.
3.  **Inclusivity**: By allowing participants to express their support for multiple proposals simultaneously, conviction voting promotes greater inclusivity in the decision-making process.
4.  **Adaptive**: The conviction voting algorithm adapts over time, making it suitable for evolving decentralized organizations.

## 5. Complementary Mechanisms

#### Quadratic Voting
Quadratic Voting <a name="quadratic-voting"></a>

Quadratic voting is a mechanism that allows participants to express the intensity of their preferences. It assigns a cost to each additional vote, making it increasingly expensive to vote in favor of or against a proposal. While it enables the consideration of minority preferences, it is still prone to manipulation and does not account for long-term commitment to decisions.
#### 

## 5. Potential Use Cases


#### Polls/rankings: Continuous TCRs
Token Curated Registries <a name="token-curated-registries"></a>

Token curated registries (TCRs) are decentralized, token-weighted lists that use economic incentives to curate high-quality content. While TCRs offer some improvements to decision-making processes, they tend to prioritize short-term gains over long-term vision, leading to suboptimal outcomes.

#### Proposal Funding via collective input (Discrete)

#### Collective Fund streaming ()

#### Osmotic Governance

https://docs.google.com/presentation/d/1Jxcpj5cgEr6-eQrabMZfawL86jWytz4atmHqiQPxFeg/edit#slide=id.g1059708dfc6_0_15

Write a short paragraph on osmotic governance as a next generation iteration of Conviction Voting:
*Osmotic governance is a next generation iteration of Conviction Voting that allows for a more fluid and dynamic delegation in collaborative decision-making process. It takes into account not only the strength of conviction, but also the distribution of opinions within a community. Through osmotic governance, voting power is distributed according to the level of agreement with a proposal, resulting in a more inclusive and democratic approach. This method encourages open dialogue and fosters collaboration among community members, promoting greater accountability and transparency in decision-making. Ultimately, osmotic governance aims to create a more equitable and sustainable society by empowering individuals and communities to take an active role in shaping their futures.*

## 5. Case Studies

*Conviction voting offers a promising approach to collective decision-making in decentralized organizations. By prioritizing long-term commitment and reducing the influence of short-term speculation, it aims to produce more stable and well-thought-out decisions. Its adaptability makes it suitable for evolving decentralized organizations, and its potential use cases range from continuous TCRs to proposal funding via collective input. While there is still much to be explored in this area, conviction voting represents a significant step forward in governance mechanisms for decentralized organizations.*

## 5. Conclusion