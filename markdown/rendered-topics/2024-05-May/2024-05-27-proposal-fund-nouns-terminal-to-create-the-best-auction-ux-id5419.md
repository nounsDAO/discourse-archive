# Proposal: Fund Nouns Terminal to create the best auction UX

<!-- ✦✦✦ POST START ✦✦✦ -->

> **Post #1 • w1nt3r**
> Created: 2024-05-27 23:02
> Updated: 2024-05-27 23:02

Hey y’all! Posting here to have a discussion before submitting a prop.

TL;DR: Fund further development of [Nouns Terminal](https://nouns.sh/) to innovate on auction UX and bring more eyeballs and money to the DAO.

### Problem

  * [nouns.wtf](https://nouns.wtf/) is being deprecated
  * The Nouns auction is the primary source of income for the Nouns DAO, but the auction UX hasn’t changed since the beginning of the Nouns project.
  * The daily auction requires active participation. 
    * DAOs looking to acquire a Noun have either a painful UX (approve each bid) or trustful solutions (send max bid to a delegate).
    * Folks outside auction time zones have to stay up late and manually place bids.
  * Arbitragers have an advantage over Nouns-aligned participants because they utilize bots to scoop up cheap Nouns to flip. Bidding bots are expensive and hard to set up for non-technical bidders.



### Solution

  * Fund an established team with a great track record within and outside of Nouns to build the best Nouns auction interface to bring more eyeballs and money to the Nouns ecosystem.
  * Build bidding automation that enables nontechnical users, folks in other timezones, and DAOs to more easily participate in the final minutes of the auction and have a higher possibility of acquiring a Noun.



### Background

2 years ago Nouns Terminal was funded by the [Nouns Clients Proof of Concepts](https://offchain.prop.house/nouns/nouns-clients-proof-of-concepts) round with 25 ETH. We focused on making a great-looking client packed with data and exploring auction bots.

[nouns.sh](http://nouns.sh) has driven 8 sales (237 ETH) via autobidder bot ([1](https://etherscan.io/address/0xab04e02792d86c522a07b19548a928d01fee2fc2#nfttransfers) & [2](https://etherscan.io/address/0xab039fda276a54f11ed57b47019efd75603c6966#nfttransfers)), been used by ~200 unique users/month, and maintained by w1nt3r.eth as a side project.

With the protocol incentives upgrade and the plans for [nouns.wtf](http://nouns.wtf) deprecation, it’s the perfect time to invest in Nouns Terminal becoming the best auction interface and a self-sustained project.

## Scope

Here’s a rough overview of the areas we’ll be working on.

### Auction Bot

  * The bot will allow anyone to passively participate in the auction by funding a bot account and setting their max bid amount per noun — the bot will place the bid in the last few minutes of the auction and only if its owner has a chance at winning a noun
  * The bids will keep moving to the next day gas-free until won or canceled
  * The UI will seamlessly integrate bot-based bids & regular bids



### New Features

  * **Price graphs.** See how Noun sales are going at a glance, aggregated by day/week/month. Easily share the graphs on social media as images or links.
  * **Bidder profiles.** 2,200+ wallets participated in the auction, yet we don’t know much about the people and their motivations. We’ll build a profile interface inside the Nouns Terminal and allow users and community members to fill them with useful data.
  * **Noun profiles.** Show details about each Noun, its traits, rarity, and origins.
  * **Auction pages.** Add a way to directly link to a specific auction with a nice-looking OpenGraph preview and Farcaster preview frames.
  * **News and changelog.** We’ll make it easy to follow the feature development and will announce big and small improvements on a daily and weekly basis.
  * **Resiliency.** Nouns Terminal will be set up to weather temporary outages of RPC providers (e.g. if Alchemy goes down, we’ll fall back to Infura or QuickNode).



### Growth

  * **Public analytics** will show how many people are using the Nouns Terminal.
  * **White glove onboarding** for the existing bidders. We’ll find and personally reach out to the most active bidders to help them onboard to the new auction interface, collect feedback, and manage feature requests.
  * **Bidding incentives.** We’ll set aside a budget to refund gas costs for participating in the auction for the first several months.
  * **Notifications system.** Subscribe to interesting auction events, e.g. when a skateboard head trait is up for sale.
  * **Social media presence.** Farcaster, Twitter, and Telegram bots share auction results daily with fun and engaging infographics alongside each post.
  * **SEO and backlinks.** Make sure the website is properly optimized and indexed by search engines. Include Nouns Terminal to user-maintained catalogs of Nounish websites.



### Open Source

  * **Documentation and templates** for deployment. It should be easy for a non-technical person to spin up a copy of Nouns Terminal on any popular infrastructure provider.
  * **No 3rd party dependencies.** Nouns Terminal is being built in a way that doesn’t depend on any proprietary data providers or SaaS tools on the critical path.
  * **Actively managed open source project.** We’ll respond to issues, accept contributions, etc. for at least 6 months during the maintenance period.



### Maintenance

  * **Oncall.** Nouns auction is a critical piece of DAO operation; we’ll ensure it runs with maximum uptime. We’ll set up automated monitoring and PagerDuty, and reserve some engineering hours through the end of 2024 to quickly respond to and resolve potential disruptions.
  * **Keep dependencies up to date.** Keeping up with NextJS versions, migrating from Ethers to viem, upgrading to wagmi2, and the latest versions of wallet connectors, so we are always taking advantage of the latest and greatest tech.
  * The long-term goal for Nouns and Nouns Terminal is to make client work self-sustained and **perpetually funded through protocol rewards**.



### Out of scope

  * The Nouns Terminal will not have any functionality related to the secondary sales except showing the secondary market floor price. Other aggregators, like Blur and OpenSea, already do a good job of showing very detailed graphs and trends. We’ll link to them where appropriate.
  * We’ll not be making changes to the core `AuctionHouse` smart contracts — it’s outside the budget for this prop. The autobidder bot will fit into the existing auction rules and will innovate within its constraints.



## Team

  * [**w1nt3r.eth**](https://warpcast.com/w1nt3r) — web2/web3 builder with 20 years of software development and product leadership experience. The original author of the Nouns Terminal, and co-founder of [BasePaint](https://basepaint.xyz/). w1nt3r will provide direction, mentorship, support, and engineering.
  * [**zherring.eth**](https://warpcast.com/zherring) — long-term crypto-designer, former Consensys, and a co-founder of [BasePaint](https://basepaint.xyz/) and [Nifty Apes](https://www.niftyapes.money/). Zach will help with the brand identity and the design of the new features.
  * [**yukigesho.eth**](https://warpcast.com/yukigesho) — web2 fullstack engineer onboarding to web3, w1nt3r’s most talented intern. Yukigesho is very excited about Nouns and has already been making improvements to [nouns.sh](https://nouns.sh/).



<!-- ✦✦✦ POST END ✦✦✦ -->

<!-- ✦✦✦ POST START ✦✦✦ -->

> **Post #2 • frog**
> Created: 2024-05-28 00:29
> Updated: 2024-05-28 00:29

Hi w1nt3r,

What are you thinking you are going to request for funding? Typically the cost of funding a proposal is the most contentious point, so if the purpose of this discourse post is to get a temp-check then adding the proposal ask might be good.

Otherwise, I think this is a solid proposal.

What happens if many people are using the bot at once? Lets say 10 people are all using the noun.sh bot, what would happen? I would think that it would take the highest max-bid of all of the users and just bid for that user.

Price graphs are interesting but simple price graph is probably not meaningfully different than what you’d be able to gauge with a dune dashboard.

Bidder profiles might be interesting to help catch if someone is starting to hoard nouns and we can see what their motivation is. Might be interesting to reward folks for filling useful data.

It might be interesting to get even more creative with bid incentives. If you are the 100th bidder you get .1 off the cost of the noun, sponsored by noun.sh (ideally your client incentives could offset this and also encourage folks to use your client)

Notifications – “get notified when a skateboard head is up for sale” why not take it step further and have the bot auto-bid for you if a certain trait is available? I would definitely love this.

I like the proposal overall!  
Good luck!

<!-- ✦✦✦ POST END ✦✦✦ -->

<!-- ✦✦✦ POST START ✦✦✦ -->

> **Post #3 • w1nt3r**
> Created: 2024-05-28 01:33
> Updated: 2024-05-28 01:33

Thanks for the feedback!

> What are you thinking you are going to request for funding?

Still running some back-of-the-envelope quotes. Currently hovering around 200k USDC, including the bot contract audit budget.

> What happens if many people are using the bot at once?

Yes, would only bid on behalf of the highest bidder.

> not meaningfully different than what you’d be able to gauge with a dune dashboard

Well I think we can do a lot better than Dune: slicker look, higher data density, and it’ll be well maintained as part of the project’s long term plan. Here’s a rough design draft:

![image](../../assets/images/5419/fa07b0d4548bfb10786609201711ba69f8cb47bc_2_690x217.png)


> Might be interesting to reward folks for filling useful data

Yep! Setting aside some budget for a “community notes” like service, someone who can pull interesting public data about an address.

> bid incentives

The rough plan is to set aside some gas compensation for bot users — i.e. if you bid via the bot, the gas is free.

> why not take it step further and have the bot auto-bid for you if a certain trait is available?

Certainly a long-term plan, but this could add significant complexity to the bot. Will definitely consider, but don’t want to commit to this as part of this prop.

<!-- ✦✦✦ POST END ✦✦✦ -->

