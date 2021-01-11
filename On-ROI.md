## Introduction

This page elaborates on Return On Investment (ROI). **Expected ROI towards growth** is a key [criterion](https://github.com/oceanprotocol/oceandao/wiki/project-criteria) in OceanDAO, in line with Ocean's [Web3 Sustainability Loop](https://blog.oceanprotocol.com/the-web3-sustainability-loop-b2a4097a36e). 

* **If you're making a project proposal, you should describe its ROI.**
* **If you're voting, you should be evaluating in terms of expected ROI.**

Therefore both proposers and voters should understand **expected ROI**. 

This page describes:
* What it is, and why OceanDAO uses it.
* Metrics to measure it in practice. Hint: go for "total OCEAN of data consumed", "network revenue" or "total OCEAN locked".
* Finally, a **worked example of expected ROI calculations**. We encourage all proposals to do this.

## What is "Expected ROI"?

It follows this equation:

#### expected ROI = bang / buck * (% chance of success)
Where 
* *bang* = value added to the Ocean ecosystem 
* *buck* = grant value spent
* *% chance of success* = e.g. an estimate by the project proposer (if you're the proposer) or by the voter (if you're the voter)

**On average, value added to the Ocean ecosystem must exceed the grant value spent.** That is, the average “return on investment” (ROI) must be > 1.0. Value added by a project is hard to know in advance. Some will fail; others will succeed and bring 10x value. But this must hold true on average across projects.

## Why "Expected ROI"?

Motivation: We want a “snowball effect” for ecosystem growth, where more funds granted leads to more funds available for grants in the future. This will happen with more network revenue or a rise in OCEAN.

Expected ROI can be lower for lower-risk projects, and needs to be higher for higher-risk projects. 

From an ecosystem perspective, if a project gets funding from outside the ecosystem, then it counts towards the value-add number, not to the value-spent number. Therefore as a project proposer, you're incentivized to get funding elsewhere too, e.g. from grants or investment, since it helps your expected ROI number. Projects that aren't working on core software should aim for their own self-sustainability over time.

For projects building apps:  Value can only be added to an ecosystem if the core product being built (by core devs) has last-mile apps for users (by app devs), which users can discover and find useful (go-to-market work). It’s a chain going from core product → dapps → discovery & usage → actual value add.

## How to Measure "Expected ROI"

Recall the equation: *expected ROI = bang / buck * (% chance of success)*, where *bang* = "value added to the Ocean ecosystem" and *buck* = "grant value spent". To compute expected ROI, we need to fill in *bang*, *buck*, and *% chance of success*. 

So how do we arrive at these values? Two are straightforward.
 * *% chance of success* is, for now, simply an estimate by the project proposer (if you're the proposer) or by the voter (if you're the voter). It could potentially use futarchy at some point, but let's not get ahead of ourselves!
 * *buck* is the grant value spent. This is denominated in OCEAN.

*Bang* is trickier, so we dedicate a whole section to it...

## What's a good metric for "bang"?

Recall that *bang* is "value added to the Ocean ecosystem." Let's discuss ways to measure it, in the context of your proposed project. 

Put another way: what metric might your project optimize, towards helping grow the Ocean ecosystem (in a sustainable fashion)?

* A first proposed metric for *bang* is "effect on the value of $OCEAN". However, $OCEAN is a function of both speculation-based and fundamentals-based factors.  Speculation-based factors are harder to pin down as metrics, yet have a significant impact on $OCEAN. This means it's harder to measure the effect of a project on $OCEAN.
* Better: let's focus on fundamentals-based factors on $OCEAN or demand for OCEAN, which have clearer metrics. Eventually these will dominate $OCEAN. And in the meantime we will focus on growing the fundamental value and associated metrics.

**Here are some of the most important fundamentals-based metrics. For estimates of ROI above, any of these will be suitable for use for the "bang" section.** 
* **OCEAN Datatoken Consuming Volume.** This is (datatoken price in OCEAN) * (no. consumes of that datatoken), summed across all datatokens. It's the best direct measure of amount of value being created in Ocean Protocol. 
* **Network Revenue.** This is the total OCEAN revenue to Ocean community taken as a % of trades or consumes in Ocean Market, etc. We can compute a fundamental valuation by simply multiplying Network Revenue by P/S (price-to-sales ratio) of e.g. 30x or 50x (ref Binance or Zoom P/S figures).   
* **Total Value Locked (TVL)**, aka Assets Under Management (AUM). This is total OCEAN staked in datatoken pools, or more generally. Demand for staking OCEAN drives demand for OCEAN and therefore drives $OCEAN. 

Here are some secondary metrics that may be useful. 
* Total revenue to all Ocean marketplace runners
* Total number of datatoken contracts
* APY for Ocean Market stakers 
* Number of weekly active users (WAUs) in Ocean Market or all markets
* Retention %, aka churn

We also welcome proposals that help OceanDAO itself. Here are some metrics of interest:
* Number of teams building on Ocean, doing outreach, or unlocking data
* $ proposed in OceanDAO (per round), and ($ proposed / $funded). The first metric gauges interest overall. The second metric shows how efficiently the capital is allocated and whether too many good proposals are left behind (too low = poor allocation; too high = too many left behind). Ideally we measure the ROI of OceanDAO funding even more directly; if you have a way, please propose it:)

## Timescales

* Q: What's a timescale for the metric to optimize across?
* A: It's up to you. If you plan to come back for a future grant, then the ideal is that you've showed ROI > 1.0 before you ask for more funds. This might be hard; therefore if you can show sufficient growth such that it will have paid off in 6 or 12 months, that's alright too. 

## Your Proposal and ROI 

* Q: Let's say you've chosen your metric. How do you write it into your proposal towards expected ROI? There's a thorn here: *buck* is denominated in OCEAN, but *bang* (one of the metrics above) might not be. 
* A: The trick is to convert it to OCEAN with some logic -- logic that you hope voters will find reasonable. The worked example below illustrates...

## Worked Example.

About your project
* You propose to reach out to your network to find lots of data publisher & buyers, resulting in more data bought & consumed.
* Metric to optimize: "$ Datatoken Consuming Volume". Secondary: "Total Value Locked". 
* Project length: 1 month.
* You believe you can get 20 data buyers (and the data buyers to sell the data that the buyers want). 
* Each buyer does 10K OCEAN / week (40K OCEAN / month) of consume volume on Ocean Market. This is a total of 800K OCEAN / month consume volume. 
* It's a recurring volume for future months.

Calculations for Expected ROI:
* Ocean Community gets 0.2% of consume volume. 0.2% * 800K / month * 12 months = approx 20K OCEAN = 20K OCEAN.
* So *bang* = 20K OCEAN. 
* Grant size = *buck* = 10K OCEAN
* So *ROI* = *bang / buck* = 20K OCEAN / 10K OCEAN = 2.0. 
* Proposer's estimate of *% chance of success* = 75%
* Final: **expected ROI = 0.75 * 2.0 = 1.5**

(We could also estimate ROI based the new publishers needing to buy OCEAN liquidity. But the approach above makes fewer assumptions.)

The expected ROI comes out nicely above 1.0. It's looks like a promising project! However the proposer's estimate of *% chance of success* may or may not be too optimistic. 
* As a voter, you should judge this. If the *% chance success* is just 50%, then expected ROI is just break-even.
* As a proposer, you should describe your proposal to maximize the voter's confidence in you and your project. The best way is: show a track record of successful projects, especially similar ones. Convince the voter! :) And remember, if you don't pull it off, it will be difficult to come back for funds in future rounds.

## Similarity to Venture Capital

To select which projects to vote for is similar to how VCs select which companies to invest in. Both are looking for a return on investment, either for the community (OceanDAO) or for investors in the VC fund. 

If you're making a proposal, you can view it similar to a pitch deck for VCs. The pitch deck includes the information for the VC to estimate bang, buck, and % chance of success (explicitly or implicitly).
- The deck gives a Total Addressable Market (TAM) which is akin to *bang*. (The VC can decide if it's reasonable, or adjust for themselves.)
- The deck (or pitcher) gives a and requested investment, akin to *buck*. 
- The deck gives a plan, team background, etc from which the VC estimates % chance of success of the team. 

You can use this framing in OceanDAO as a proposer or as a curator (voter):
- If proposing: write your proposal as a pitch deck. 
- If voting: pretend you're a "VC" for OceanDAO

OceanDAO is best suited for the early-stage funding ("pre-seed" or "seed funding" stage). Therefore the ROI calculations could be based on the team using OceanDAO grant as part of the early-stage funding, and using 3rd parties for all other funding, which leads to a very good expected ROI as well.

