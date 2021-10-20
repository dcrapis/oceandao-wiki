# Logistics

- Voting will take place on: [vote.oceanprotocol.com](https://vote.oceanprotocol.com/).

- See all of the proposals [here](https://port.oceanprotocol.com/c/oceandao/56); filter by round.

- Questions? [join the Discord conversation](https://discord.com/channels/612953348487905282/776848812534398986).

# How To Vote

![](https://github.com/dcrapis/oceandao-wiki-files/blob/main/voting-oceandao.png)

**Single Ballot:**
- Once voting begins you will see the active proposals. Starting in R11, all Grant Proposals will be listed in a *single voting ballot*. This means that you can use your OCEAN tokens *once* to vote Yes or No on proposals (Note: this is different from previous rounds that had one Yes/No ballot for each proposal and you could use all your ocean repeatedly on different proposals).

**Voting:**
- Connect your Web3 wallet containing your OCEAN tokens.
- Select the fraction of OCEAN tokens you want to allocate to each preference. 
	- In the example, we are voting with 10% of our OCEAN for `Acute Apple - Yes`, 20% for `Oblong Orange - Yes` and 70% for `Artisanal Banana - No`.
	- If we have 1,000 OCEAN in our wallet this will allocate 100 OCEAN, 200 OCEAN, and 700 OCEAN respectively.
- Click `Vote` and Sign with your wallet (Note: there are no gas fees, no ETH required, and OCEAN tokens never leave your wallet).

**Results:**
- The current results tab will adjust accordingly as votes are counted.
- XXX The proposals with the highest votes will receive grants based on how many grants will be distributed in the current round. 

Note: the vote counts the amount of OCEAN in your wallet and OCEAN staked on Ocean Market. No OCEAN will be taken from your wallet. Again: it is a gasless transaction and there is no fee.

# Voting Parameters:

- At proposal deadline (the first day of every month at 23:59 pm GMT), Proposals that meet the “Project Criteria” will be migrated to the OceanDAO Voting Page.

- Vote with your OCEAN Tokens in your wallet or staked on Ocean Market.

- Votes are counted using [Quadratic Voting](https://en.wikipedia.org/wiki/Quadratic_voting) (QV): for each proposal that you vote on, your voting weight is the square root of the OCEAN you voted with.

- In order for your vote to count, you must have the OCEAN already in the non-custodial wallet you plan on voting with before the vote opens (the first day of every month at 23:59 pm GMT) or staked on the Ocean Marketplace. This is so your existing OCEAN balance can be counted. Voting from exchanges is not supported.

- Your wallet address can only vote on one proposal. If you would like to vote on more than one proposal, you will need to fund your multiple wallet addresses with the respective amount of OCEAN before the voting opens.

- You can only vote with the OCEAN tokens in your wallet or staked on Ocean Market. You will be unable to vote with OCEAN that is deposited as liquidity in Bancor, Uniswap, or otherwise. It is your choice if you would like to remove liquidity, vote, and re-add the liquidity back later from AMMs. Risks come with removing liquidity (impermanent loss etc). This is up to you to manage.

- Voting with staked OCEAN in Ocean Market: your initial voting power in Snapshot will reflect how many OCEAN as ERC20 are in your wallet. However, once you cast your vote and if staking, your number of OCEAN on the marketplace will then be included.

# FAQs

1/ What does it mean that the quadratic voting weight is the square root of the OCEAN tokens?

- Your total OCEAN allocated to a proposal is converted to VOTES using the rule `N OCEAN -> square_root(N) VOTES`.

For example:

| OCEAN      | VOTES |
| ---------- | ---------- |
| 1      | 1       |
| 4   | 2        |
| 9   | 3        |
| 16   | 4        |


2/ Why are we using QV and not traditional voting?
- QV balances “one person one vote” (democratic ideal) with “one token one vote” (skin-in-the-game).
- QV gives voice to smaller holders and softens the impact of whale voters while still acknowledging higher skin-in-the-game.

# Resources

- To learn more about QV visit this link