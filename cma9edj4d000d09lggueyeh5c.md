---
title: "Simply Put: Bittensor Emissions & Protocol-Injection"
seoTitle: "Emissions & Protocol Injection"
seoDescription: "Bittensor incentive mechanism: Emissions and Protocol-injection in a nut shell."
datePublished: Sun May 04 2025 08:36:14 GMT+0000 (Coordinated Universal Time)
cuid: cma9edj4d000d09lggueyeh5c
slug: simply-put-bittensor-emissions-and-protocol-injection
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1746347744915/8a6873d0-2b7e-4eb8-9827-7473c05af792.png
tags: tao, bittensor, dtao

---

*Bittensor is mined in a similar fashion to Bitcoin with one major distinction. <mark>Bitcoin miners</mark> aim to <mark>solve a math puzzle</mark> by trial and error, racing to be the first to find the solution and secure the network. Where as, the compute from <mark>miners on Bittensor</mark> is used to solve real value generating problems for the subnets, like powering prediction & discovery AI models (*[*Nova*](https://www.metanova-labs.com/)*,* [*Gaia*](https://gaiaresearch.ai/)*,* [*Bettensor*](https://www.sportstensor.com/)*), or training AI models (*[*Templar*](https://www.tplr.ai/)*) and inference (*[*Targon*](https://targon.com/)*). In both, this process helps the blockchain grow one block at a time, releasing (emitting) the underlying token little by little to the network.*

## What are Emissions?

Emissions are the process of creating new TAO tokens in Bittensor, slowly releasing them into the network over time. It’s the deal between the network and it’s miners and validators who get rewarded TAO for effectively solving problems provided by the Subnets (companies and projects built on Bittensor using their infrastructure)

Over time, just like Bitcoin, the rate of emission will halve periodically, reducing the amount of new TAO created per block and making the token harder to mine. Emission continue to be emitted until the total supply of 21 million TAO is reached.

## What is Protocol Injection?

Protocol injection is a rewarding system which injects TAO tokens to network participants based on their performance. The idea here is simple: to incentivize and reward network participants who are driving the network in the right direction.

All the TAO tokens used for protocol injection (as rewards) are newly minted tokens, meaning that they were created as part of Bittensor’s emissions.

A spike in rewards can be caused by an EMA smoothing effect, which delays the reward distribution changes just enough to ensure that validators are incentivized to provide consistent results over time.

## Who Gets Rewarded & Why?

### Who:

Subnets, miners, and validators get rewarded directly. Through them, all participants—including investors (nominators, also called delegators) and subnet owners—are rewarded indirectly. For example, if a subnet earns more TAO, the people who have invested in that subnet by staking their tokens benefit as the subnet grows in value. Similarly, validators who earn more TAO share those rewards with the people staking through them, as their increased TAO weight leads to a bigger portion of the emissions.

### Why:

This happens because of the Yuma Consensus—a system that acts like a “Proof of Intelligence” for the network. It gathers input from validators to figure out who’s contributing the most value. Validators in the Root Subnet (SN0) rank validators of other subnets, who in turn rank the miners. The Yuma Consensus combines these rankings (validator rank × miner rank = overall miner rank) to decide how TAO rewards should be distributed.

### What Is Being Measured?

* **Contribution Quality (Proof of Intelligence):** How well miners solve problems, like building accurate AI models.
    
* **Validator Rankings:** How validators rate the miners’ work and how well they align with the network’s overall opinion.
    
* **Subnet Performance:** How much value a subnet brings to the network, based on its activity and results.
    

### How Often Does This Happen?

Rewards are injected with every new block on the <mark>Subtensor</mark> blockchain (every 12 seconds). Currently, in a single day, this adds up to 7,200 TAO being injected into the network, shared among subnets, miners, and validators based on their performance.

*<mark>Subtensor</mark> is the main blockchain that powers Bittensor recording all the work done by miners and subnets.*

## TL;DR

Emission is the creation of new TAO tokens.

Protocol injection coming from emissions, is how newly minted tokens are distributed to the network as rewards to participants who are doing valuable work, like running AI models or validating miners. It’s an incentivizing mechanism for people to contribute useful work, like building better AI, while keeping the network fair and competitive.

*Rewarding those who add the most value, Bittensor ensures the network grows stronger over time, benefiting everyone involved.*

All protocol-injected rewards come from emissions, but not all emitted TAO is immediately injected - it’s distributed based on performance (which has delays set in place like EMA smoothing to incentivize stability).

### Key Words

#Bittensor, TAO, Protocol-Injection, #Yuma Consensus, #Subtensor, #Nominator, #Delegator, #Emissions