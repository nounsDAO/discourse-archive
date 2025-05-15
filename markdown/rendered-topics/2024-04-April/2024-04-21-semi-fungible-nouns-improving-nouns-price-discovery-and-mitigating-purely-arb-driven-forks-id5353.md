# Semi-fungible Nouns: Improving Nouns price discovery and mitigating purely arb-driven forks

<!-- ✦✦✦ POST START ✦✦✦ -->

> **Post #1 • delken**
> Created: 2024-04-21 18:36
> Updated: 2024-04-21 18:36

NFTs tend to have much thinner liquidity than ERC20s, for obvious reasons. Using it across DeFi is cumbersome: each NFT begets its own prices, liquidity is fragmented, and markets become less efficient. CEX / DEX listings are a no-go, lending/borrowing must be done in unorthodox ways, and perps become a headache to implement, just to name a few.

However, NFTs are made non-fungible for a reason: they convey a sense of identity for its holders, and in the case of NounsDAO, form the brand itself. Nouns wouldn’t be Nouns if Noun 1 and Noun 4392 is rendered the same.

I propose a middle-ground: a wrapper service for Noun holders to deposit Nouns in exchange for fungible tokens (say, $NOUNS). The tokens would then be regarded as a representative of its underlying NFT in the escrow, and could be used across DeFi (e.g., Uniswap, Aave, etc.) just like your typical ERC20s.

The rate of $NOUNS per Noun NFT is fixed: say, 100 $NOUNS per 1 Noun NFT. The Noun in escrow will be pooled together with other deposited Nouns — no distinction is given. This means that any given holder of 100 $NOUNS units could redeem for any Noun deposited in escrow on a first-come first-served basis.

Price of $NOUNS is proportionate to the price of a Noun: 100 $NOUNS = 1 Noun NFT. It’d be similar to Pandora’s “ERC404” (I wanted to avoid mentioning names TBH), but instead of burning the NFT, we’d be keeping them in escrow for any holder of Nouns to redeem.

The hope is that with a fungible representation of Nouns, we could have better price discovery for Noun NFTs, which would contribute towards closing the arbitrage gap of each Noun’s BV (Book Value) to its secondary market price. Nouns would see more efficient markets, and purely arbitrage-driven forks would become increasingly rare as a result. Instead of tweaking further with our forking mechanism (which is sound enough IMO), perhaps the problem could be solved by simply having a more efficient market and better liquidity for Nouns?

To bootstrap initial liquidity, we could use a certain number of non-treasury Nouns (570 NFTs according to [Dune @beetle](https://dune.com/queries/2980812/4944877)) and deposit it in escrow to mint $NOUNS. NounsDAO could then elect a council / team to maintain $NOUNS operations: deploying the escrow-and-mint contract, setting up the Uniswap pool, handling listing on CEXs, or integration with Aave and other DeFi protocols.

Not expecting this to be seriously considered for proposal in the near future, but as a fellow Noun, I hope my post above could at least be a point of contention and spark further discussions within the Nouns community.

<!-- ✦✦✦ POST END ✦✦✦ -->

