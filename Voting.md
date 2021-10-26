# Logistics

- Voting will take place on: [vote.oceanprotocol.com](https://vote.oceanprotocol.com/).

- See all of the proposals [here](https://port.oceanprotocol.com/c/oceandao/56); filter by round.

- Questions? [join the Discord conversation](https://discord.com/channels/612953348487905282/776848812534398986).

# How To Vote

![](https://github.com/dcrapis/oceandao-wiki-files/blob/main/voting-oceandao.png)

Once voting begins you will see the active proposals that you can vote on.

**Single Ballot:**
- Starting in R11, all Grant Proposals will be listed in a *single voting ballot*. This means that you can use your OCEAN tokens *once* to vote Yes or No on proposals (Note: this is different from previous rounds that had one Yes/No ballot for each proposal and you could use all your ocean repeatedly on different proposals).

**Voting:**
- Connect your Web3 wallet containing your OCEAN tokens.
- Select the fraction of OCEAN tokens you want to allocate to each preference. 
	- In the example, we are voting with 10% of our OCEAN for `Acute Apple - Yes`, 20% for `Oblong Orange - Yes` and 70% for `Artisanal Banana - No`.
	- If we have 1,000 OCEAN in our wallet this will allocate 100 OCEAN, 200 OCEAN, and 700 OCEAN respectively.
- Click `Vote` and Sign with your wallet (Note: there are no gas fees, no ETH required, and OCEAN tokens never leave your wallet).

**Results:**
- The current results tab will adjust accordingly as votes are counted.
- In each round there will be a total funding amount available. Proposal that receive 50% or more "Yes" votes receive a grant and any remaining funds not granted are burned.

Note: the vote counts the amount of OCEAN in your wallet and OCEAN staked on Ocean Market. No OCEAN will be taken from your wallet. Again: it is a gasless transaction and there is no fee.

# Voting Parameters

- At proposal deadline (the first Tuesday of every month at 23:59 pm GMT), Proposals that meet the “Project Criteria” will be migrated to the OceanDAO Voting Page.

- Votes are counted using Quadratic Voting (QV): for each proposal that you vote on, your voting weight is the square root of the OCEAN you voted with. (See FAQ 1 below for more details.)

- Vote with your OCEAN Tokens in your wallet or staked on Ocean Market.
	- In order for your vote to count, you must have the OCEAN already in the non-custodial wallet you plan on voting with before the vote opens (the first Thursday of every month at 23:59 pm GMT) or staked on the Ocean Marketplace. This is so your existing OCEAN balance can be counted. Voting from exchanges is not supported.

	- You can only vote with the OCEAN tokens in your wallet or staked on Ocean Market. You will be unable to vote with OCEAN that is deposited as liquidity in Bancor, Uniswap, or otherwise. It is your choice if you would like to remove liquidity, vote, and re-add the liquidity back later from AMMs. Risks come with removing liquidity (impermanent loss etc). This is up to you to manage.

	- Voting with staked OCEAN in Ocean Market: your initial voting power in Snapshot will reflect how many OCEAN as ERC20 are in your wallet. However, once you cast your vote and if staking, your number of OCEAN on the marketplace will then be included.

# FAQs

**1. How does QV in OceanDAO work?**

- Your total OCEAN allocated to a proposal is converted to VOTES using the rule `N OCEAN -> square_root(N) VOTES`. For example:

| OCEAN      | VOTES |
| ---------- | ---------- |
| 1      | 1       |
| 4   | 2        |
| 9   | 3        |
| 16   | 4        |

- Then, the VOTES are summed up, and every proposal's sum of VOTES is taken to the square again. This is the voting outcome. 

- You can view the simulation/example of QV (and QF, a variant of this mechanism) in Ocean provided by the Token Engineering Community in this [spreadsheet](https://docs.google.com/spreadsheets/d/1kxyfD60BZB6eKgB7VqP45_4ct0dcK5fXzKVddJZk7C4/edit#gid=0).

**2. Why are we using QV and not traditional voting?**
- QV balances "one person one vote" (democratic ideal) with "one token one vote" (skin-in-the-game).
- QV gives voice to smaller holders and softens the impact of whale voters while still acknowledging higher skin-in-the-game.

# Resources

Ocean
- OceanDAO Round 11 announcement [blog post](https://blog.oceanprotocol.com/oceandao-round-11-is-live-2b8ea0205074)
- Video tutorial for the main sections above - [youtube](https://www.youtube.com/watch?v=Err1BpERDiQ)

Technical
- QV implementation on Snapshot: [docs](https://docs.snapshot.org/proposals/voting-types#quadratic-voting), [code](https://github.com/snapshot-labs/snapshot/blob/develop/src/helpers/voting/quadratic.ts) - note: the QV module at snapshot is an implementation of the Liberal Radical Mechanism (LR) according to Definition 7 in ["Liberal Radicalism: A Flexible Design For Philanthropic Matching Funds", Buterin/Hitzig/Weyl, 2018](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3243656).
- Vitalik Buterin's quadratic payments primer [blog post](https://vitalik.ca/general/2019/12/07/quadratic.html)
- Quadratic voting with matching pool original paper from Buterin, Hitzig and Weyl - [technical paper](https://arxiv.org/pdf/1809.06421.pdf)
- Deep dive into QV efficiency - [technical paper](https://export.arxiv.org/pdf/2010.01193v1)
