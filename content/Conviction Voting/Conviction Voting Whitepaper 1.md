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

# Conviction Voting: A New Paradigm for Collective Decision-Making

**Table of Contents**

1. [Introduction](#introduction)
2. [Background](#background)
3. [Key Concepts](#key-concepts)
    - [Conviction Voting](#conviction-voting)
    - [Token Curated Registries](#token-curated-registries)
4. [Implementation](#implementation)
    - [Setting Parameters](#setting-parameters)
    - [User Interface](#user-interface)
5. [Advantages and Limitations](#advantages-and-limitations)
6. [Conclusion](#conclusion)

<a name="introduction"></a>
## 1. Introduction

As communities and organizations grow in size and complexity, making collective decisions becomes increasingly difficult. Traditional voting mechanisms, such as simple majority or rank-choice voting, often struggle to capture the nuances of a diverse community. Conviction voting is an innovative solution that seeks to overcome these challenges by allowing participants to express not only their preferences but also the strength of their convictions.

This whitepaper aims to provide a comprehensive overview of conviction voting, including its background, key concepts, implementation strategies, advantages, and limitations.

<a name="background"></a>
## 2. Background

Conviction voting was first proposed by Giveth, a decentralized organization focused on building tools for the future of giving. The concept was inspired by the research of Jennifer Lyn Morone, who argued for a more nuanced approach to decision-making that takes into account the intensity of participants' preferences.

Conviction voting is a novel approach that combines continuous voting with token-weighted decision-making. It allows users to vote for multiple proposals simultaneously and continuously, while also taking into account their stake in the community and the duration of their support for each proposal.

<a name="key-concepts"></a>
## 3. Key Concepts

<a name="conviction-voting"></a>
### 3.1 Conviction Voting

In conviction voting, participants vote with tokens representing their stake in the community. The weight of each vote is determined by both the number of tokens and the duration of support for a proposal. The longer a participant supports a proposal, the more "conviction" their vote accumulates.

By continuously adjusting the weight of each vote based on duration, conviction voting creates a dynamic environment that incentivizes long-term commitment and thoughtful decision-making. This is in contrast to traditional voting methods that encourage short-term thinking and tactical voting.

<a name="token-curated-registries"></a>
### 3.2 Token Curated Registries

Token curated registries (TCRs) are decentralized, community-driven lists of high-quality resources or assets. In a TCR, token holders collectively decide on the inclusion and ranking of items within the registry. Conviction voting can be used within a TCR framework to facilitate decision-making and ensure the quality of the curated list.

<a name="implementation"></a>
## 4. Implementation

<a name="setting-parameters"></a>
### 4.1 Setting Parameters

Implementing conviction voting requires the definition of several parameters, including:

1. **Token**: The token used to represent stake in the community.
2. **Conviction Growth Rate**: A factor that determines how quickly conviction accumulates over time.
3. **Minimum Conviction Threshold**: A minimum amount of conviction required for a proposal to be eligible for funding or acceptance.
4. **Proposal Funding**: The allocation of funds or resources for accepted proposals.

<a name="user-interface"></a>
### 4.2 User Interface

A user-friendly interface is crucial for encouraging participation in conviction voting. The interface should allow users to:

1. View and submit proposals.
2. Allocate tokens to support multiple proposals simultaneously.
3.