# Rewarding the profitless - Layer-2

## What is Layer-2?

Another peculiarity of saNFTs is layer-2: Because of it, in the event that some owners are not profitable, for lack of volume after their purchase, there will still be some rewards for them.\
Because of this, the degree of risk for the purchase decreases, incentivizing new buyers.

## How it Works

### Funding Layer-2

Each time that the pool account is redistributed (according to [Layer-1](volume-pools-layer-1.md)), a percentage of it goes into a reward pool, associated with a specific saNFT.

### Conditions to Trigger the Rewards

When in a specific period of time the volume is below a certain percentage of the volume of buy offers in the previous same period of time, rewards are triggered. (this is a tricky concept, see the [example](rewarding-the-profitless-layer-2.md#example) to make sure you understand it correctly).

### Rewarding

Once rewards are triggered, the amount of lumens in the reward pool is distributed among the current owners in the network who have not yet profited, thus have not earned back at least the amount of XLM they offered for the saNFT. Each one of these owners will be rewarded proportionally to their current “loss”.

### Example

Considering that for a saNFT the period of time to be considered for evaluating the level of volume is 3 months and the percentage of volume with respect to the previous period below which the reward account is to be distributed is 10%. This means that if after 6 months (3 months + 3 months) there are only three owners in the current network which are still not in profit, and the volume of buy offers in the last 3 months is below 10% the level of buy offers in the previous 3 months, the whole amount in the reward pool will be distributed among these three owners. If owner A has a current loss of 500 lumens, and the two others (B and C) of 250 lumens each, owner A will receive 50% of the reward pool, since he has 50% of the total losses, while B and C will receive 25% of the rewards each.\


### Nothing to Lose

It's worth noting that after the distribution of the rewards, these owners will still be able to earn through [Layer-0](layer-0.md).

## Why Layer-2

Layer-2 is an effective way to decrease the level of risk associated with buying saNFTs. Large reward pools for unprofitable owners can easily attract new buyers, which is good for the protocol according to [Layer-0](layer-0.md) and [Layer-1](volume-pools-layer-1.md).
