# OUSD: Private, Instant, USD

### Introduction

A dollar bill is a simple thing. You can hold it, you can spend it, you know its value, and you can freely use this measure of value to exchange for other goods.

In 2008, Satoshi Nakamoto laid out his vision for creating digital cash. Next came Bitcoin. And then a whole world of digital currencies sprung into life. Anyone who knows anything about cryptocurrency knows how volatile they can be. Values skyrocket. Values plummet. It’s the wild west of finance.  
 
Due to the erratic nature of cryptocurrency valuations, stablecoins have risen as the best to hold cryptocurrency assets without being exposed to price volatility and facilitate trades between unconnected blockchains. The stablecoin market is fast approaching 100 billion US dollars. It’s a hugely important part of the entire ecosystem.

However, a stablecoin is not simply a digital dollar bill. Digital cash has come a long way, but there is a long way to go. Cash is private, while most blockchains are not. Stablecoins which rely on non-private blockchains do not fully embody the ideals of digital cash.

Traditional finance has a slew of problems which are being addressed by the cryptocurrency and blockchain ecosystem, however, there is a lacking replacement for the stability and fungibility of cash.

There have been some attempts to make private stablecoins, however they are badly flawed in ways which shall be explicated herein. Using the privacy coin OXEN and its existing service node network, we can create a faster, simpler, and stronger version of a privacy stablecoin – OUSD.

Satoshi wanted to design a system for digital cash. OUSD is a new design for the same vision. OUSD is digital cash.

**Fast facts**

  - $OUSD CAN BE SENT INSTANTLY USING OXEN’S BLINK TECHNOLOGY
  - $OUSD IS BACKED 1:1 USING $DAI
  - $OUSD TO $DAI CONVERSIONS TAKE JUST 2-4 HOURS
  - NO RELIANCE ON CHAINLINK OR CENTRALISED ORACLES
  - NO RUN ON THE BANK SCENARIO
  - DECREASES MARKET MAKER RISK
  - NOT VULNERABLE TO HASH ATTACKS
  - ENVIRONMENTALLY SUSTAINABLE (PoS)

**The problem**

The majority of stablecoins are based on blockchains which make many transaction details traceable. This is an unacceptable compromise for people who want to preserve their privacy.

The interest in Haven shows a clear appetite for a private stablecoin. However, Haven and its xAssets are doomed to fail. It is not a viable long-term solution, and multiple improvements should be made to their design in order to actually create stable digital assets.

What’s the point of a stablecoin? To stay as close to the price of whatever asset it is pegged against. In order to truly achieve this, the stablecoin needs to be backed by a valuable and widely recognised asset with strong fundamentals. If the value of the asset supporting the peg cannot be guaranteed, neither can the stablecoin itself. XVH does not have inherent value, it is all based on its ability to facilitate stable assets. If enough people decide they want to ‘claim’ their stored value and convert back to XVH, the price of XVH could quickly spiral downwards and cause the entire market to crash.

Stablecoins also need to facilitate trading or be used as a store of value. Haven’s approach will simply never achieve this. The overly complex and high-fee nature of converting XVH to pegged assets makes it extremely unattractive and borderline unusable. This can be very clearly seen by the lack of adoption and trade volume using xUSD and other xAssets.

|Swap Speed | Fees |
|--|--|
| 6 Hours (Fastest Possible swap) | Base transaction fee , Flat conversion fee 0.2%, Speed fee 5%, Speculation fee charged on profit 50-10%, Spot/MA fee 110% |
|2 days | Base transaction fee , Flat conversion fee 0.2%, Speed fee 2%, Speculation fee charged on profit 10%, Spot/MA fee 100% |
| 5 Days | Base transaction fee , Flat conversion fee 0.2%, Spot/MA fee 75% |
| 10 Days (Slowest Possible swap) | Base transaction fee , Flat conversion fee 0.2%, Spot/MA fee 25% |


The reality is, average users are not going to wrap and unwrap tokens, especially given the convoluted nature of doing so with XVH. Because of that, the burden falls on market makers, but the risk of market making for Haven’s assets is simply too high, leaving barren, inactive, and illiquid markets.

On top of all of this, Haven is not truly programmatic. [Haven re-oracilizes through centralised endpoints controlled by Haven developers](https://github.com/haven-protocol-org/haven-offshore/blob/master/patches/src/cryptonote_core/blockchain.cpp.patch#L778), **meaning they have full control over the swap price between XVH and stable assets**. This is not okay, it is not secure, and it is not decentralised.

There must be a better solution for a private stablecoin.

**The solution**

First, we need to find a privacy coin with both inherent value, a strong network, and a versatile protocol. The answer is clearly OXEN.

OXEN and its underlying service node network have already made improvements to Monero that make it more suitable as a stablecoin, most importantly instant transactions. Instant private transactions is a game-changing technology, and being able to leverage this in the context of a stablecoin creates an opportunity for a private stablecoin that actually has a good user experience.

Instant settlement. Low fees. Uncompromising privacy.

The first asset to be created using OXEN will be OUSD, a private digital asset pegged to USD. OUSD is a coloured coin on the Oxen blockchain, any number of coloured coins could be created in the future pegged to different assets like gold or oil.

OUSD retains all the qualities of OXEN, including ring signatures, stealth addresses, bulletproofs, checkpointing, and instant transactions.

OUSD will be created using a combination of OXEN and DAI, and the entire OUSD asset will be backed 1:1 with DAI, one of the most reliable and trusted stablecoins in existence.

OUSD will be minted by depositing DAI into the OUSD Ethereum smart contract alongside an Oxen wallet address. The service node will then witness and verify the deposit on the Ethereum blockchain. New OUSD can be minted in 4 hours, not weeks.

Market makers will have extra confidence. Users will have a better experience. OUSD is connected to a token with inherent value, with a longstanding network.

The Oxen service node network is easily capable of supporting the creation and management of stable assets, however it will introduce some additional load on the network. Because of this, the network should be incentivised to support the OUSD infrastructure.

The OUSD contract should allow for staking of deposited DAI into decentralised lending protocols or as liquidity in AMMs like Curve, YFI, or Compound.finance. These yields can be programmatically captured in the contract and used to buy and burn wOXEN, returning value directly to the Oxen network.

The result is the most feature rich, reliable, and trustworthy private stablecoin in existence.

OUSD is the privacy stablecoin we’ve been waiting for. OUSD is the privacy stablecoin we need.

The full technical paper can be read [here](https://github.com/BorislavBabochka/OUSD/blob/main/OUSD_Paper.pdf)
