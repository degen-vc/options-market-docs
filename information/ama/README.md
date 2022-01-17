---
description: >-
  Here is the genesis of the idea, and how we are doing things completely
  differently!
---

# 📜 Founding AMA

### What is Options.Market?

Options.Market will begin life as a fork of a VC-backed anon-project called SirenMarkets.com, which is an open source mainnet, decentralized options trading solution for ERC20 tokens. The potential is to create a fully-composable cryptocurrency options trading solution with embedded liquidity incentives that allows traders to move in and out of the long and short sides of options seamlessly and enables more complex portfolio positions in DeFi than are currently possible. As such, it is a market that will scale with DeFi even as DeFi continues to take ground from traditional finance . In traditional finance, options see $300 trillion of notional volume traded every year.

### **Why did you decide to do this?**

DegenVC is able to effectively front-run VC-backed open source DeFi projects due to its large committed community that want to be first to own project tokens, its track record in delivering alpha, and its massive war chest of dev runway. Our capacity in AMM, DEX and bonding curve innovation and our doxxed team’s vast experience with innovative financial instruments make this fork an obvious choice.

### **Why do you think it will be successful?**

Mainly because of our three-pronged approach:

1. **Launch** - the alphadrop / accelerator-vault combo is unstoppable
2. **Improve** - we will continue to senior-dev war room the code and solution, improving on it prior to our launch (circa 30 days)
3. **Tokenomics** - liquidity providers are the key ecosystem partner. We have allocated 5x rewards to them and will not lock their rewards at all (Siren impose 3 months). Even though we launch later our liquidity providers will actually receive reward tokens sooner.

Our core belief is that the market should be allowed to decide if projects succeed or not. As it is constructed, the markets have very little say in relative success or failure in Siren as a sizeable quantity of tokens have been sold at highly discounted prices. This reminds us all too well of the ICO boom of 2017/2018 - influential and connected investors getting in on projects at deep discounts to the retail market. Indeed - what is different from a normal centralized VC-type transaction? Very little in our analysis.

### **Where can you improve on the project you fork?**

Firstly, we should speak to “why fork”. We fork when we realise we can be at the same developmental life-cycle stage today as a project is by doing so. Absent of the liquidity Siren currently has, this is true. But this is not typically enough. There must be more that we can add. Degen Labs brings the following 3 incremental improvements and ideas:

1. **A key concern in Siren’s technical architecture is** [**this function**](https://github.com/sirenmarkets/core/blob/c5c8cb92bea9e7fbf21186723ac1a85168ab444e/contracts/token/SimpleToken.sol#L116) **in the w/b token source code: (**[**https://github.com/sirenmarkets/core/blob/c5c8cb92bea9e7fbf21186723ac1a85168ab444e/contracts/token/SimpleToken.sol#L116**](https://github.com/sirenmarkets/core/blob/c5c8cb92bea9e7fbf21186723ac1a85168ab444e/contracts/token/SimpleToken.sol#L116)**)**, which allows the anon owner of the token contract to self-destruct it. We assume this allows the Siren anon team to shut down and drain the AMM for upgrade or whatever but it amounts to them having the power to delete all tokens and value. This is one of the reasons they have a closed AMM. Their ERC20’s are more like bonds which are short lived and vanish. One less risky solution would be to allow the derivative coins to collapse into simple collateral-backed coins when their time is up (for example, like how SAI went from dollar pegged to having a fixed redeem rate for eth). Then we could list on generic AMMs with all the liquidity advantages. We are looking at writing an adaptor that copes the destruct somehow. Details to follow on Github.\

2. **Like most projects with “governance tokens”, governance itself is something deferred in favour of essentially retaining full control “for the time being”.** Degen Labs has a mainnet functioning DAO currently used on Behodler, MorgothDAO. This will be utilised for real decentralized governance from the outset.\

3. **Siren claims that fees will be distributed to SI token holders.** Really? How? It's a SAFT-funded project so what about KYC? Options.Market will send fees to a decentralized liquid vault where people can claim LP tokens at a discounted value but locked for a certain period. This will support the OSM token through buy-pressure and liquidity locking. Once this liquid vault is deployed the Github link will be shared.

### **What do you expect will happen?**

Honestly, this is one for our community and we will be focused on the roll out more than the Uniswap market. If the price is low, it's more opportunity for our community to accumulate in the early stages which we like. Only the Degen community will really understand the potential of a project with just a telegram group and this AMA but that is Degen Labs backed.&#x20;

They have been part of the $12MM+ alphadrops over the past six months so they know what is coming. At this point we don’t need a snazzy website to convince them about the idea and its potential. We just need some clear information and a well managed telegram channel. Then we get on with building.

If you are new to Degen VC we would encourage you to read [this article](https://medium.com/degen-vc/calculating-returns-to-degenvc-lps-fcf342abb338) that unpacks the data around the alpha we have delivered via alphadrops in six months.

### **How do you expect to compete with a VC backed project?**

There are two sides to this answer. One, competing on the talent side, and two, competing on the resources side. Degen Labs has the talent - this has been demonstrated in Behodler.io and other projects. It also has the resource enough to fund years of development. Our developers are paid well but not fifty millions of dollars like the Siren team - all this money goes to the degen community.

We think that in the token paradigm VCs really just serve the purpose of vetting and are not needed for financing. Also, the way this project has structured its token distribution is to support the token price of VCs bags for as long as possible which will also serve as price discovery for the #degenhorde-backed options.market. This will be useful too.

### **What are the distribution differences between this structure and the way Siren is set up?**

* 18% of the supply was sold to VCs at $0.40 per token. They have to wait just a year before being able to dump on retail.
* 10% went to an “incubator” (another VC).&#x20;
* Only 5% of the supply is being offered to the public via the Balancer LBP. Most tokens sold on the Balancer LBP at the time of writing have sold for over $2 each (5x what the VCs paid).&#x20;
* Just 6.5% is being offered as liquidity rewards.&#x20;
* The “initial team” (anons) is keeping 26.5% of tokens worth $10.6 million at VC prices or $53 million at LBP ($2) price.&#x20;

### **The Degen VC approach is radically different:**

* 18% of the supply will be given at **ZERO COST** to the #degenhorde (DGVC LP) in an #alphadrop
  * When: March 12th, 2021.&#x20;
* 10% of the supply will go to an accelerator-vault to boost liquidity&#x20;
  * When: March 19th, 2021.&#x20;
* 32.5% will reward liquidity providers (5x rewards of Siren with no lockup)&#x20;
  * All locked for in team.finance 30-days prior to launch of pools.
* 4.5% will be allocated to community rewards.
* 35% of the supply will go to Degen VC for project finance and marketing.&#x20;
  * 25% in team.finance lock for 30-days.&#x20;

### _**0% will go to VCs**_

### **-----------------------**

### **Siren Project Assessment**

From what we can understand of the published material, the founding team of SIREN has raised millions of dollars for the development and marketing of the ecosystem and yet still retain 26.5% of total token supply on a lock-up vesting period.

This means that they effectively get 2 funding / exit bites: the first one is VC funding to execute their roadmap: pay salaries and pay for dev, marketing and other expenses; the second is the team token allocation that commences unlocking in 1 years’ time - not a dev wallet in the purest sense - and are then sellable into the market. It’s a founder and team equity-kicker on top of a fully-funded execution roadmap. It’s an old-school VC construct shoe-horned into tokenized environment. We wish them well, but we want to make degens wealthy, not VCs. So LFG.

