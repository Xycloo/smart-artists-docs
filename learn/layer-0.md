# Layer-0



Layer-0 is the core mechanism behind saNFTs, learning this concept ensures an in-depth understanding of the basic dynamics of a saNFT.

## Buying a saNFT

saNFTs are very different from NFTs. If you already dug into stellar smart contracts you've probably come across the work of [tyvdh](https://twitter.com/tyvdh) and his smart NFTs. saNFTs are by themselves smart NFTs (they are part of the saProtocol). This means that when you buy one, you will not just pay and receive the asset, rather you will do much more.

### 1. Entering the Network

When you acquire a saNFT, you buy a slice of the saNFT’s ownership network, thus becoming part of the network itself. The size of your slice in the network depends on your **buy offer**, that’s why you will choose how much to invest in a saNFT. Your slice will be calculated in percentages according to the all-time amount of lumens that have been spent on that saNFT, see [the formula](../technical/formulas.md#network-slice-of-an-owner).&#x20;

### 2. Earning

Each time a new buyer steps in, their **buy offer** will be distributed between all the owners according to their percentage of ownership. The rewards are calculated with [this simple formula](../technical/formulas.md#owner-earns-in-xlm). It goes without saying that every time a new owner steps into the network, these percentages (after the new owner’s buy offer is distributed) will be adjusted as there will be more total\_xlm and more owners.&#x20;

### 3. Funding Layer-1

It’s important to say that a percentage of the buy offer will go straight to power the LAYER-1 earning mechanism.&#x20;

### 4. Supporting the Artist

All of this, while a percentage of the buy\_offer will go straight into the artists’ wallet with no fees taken by smart artists.&#x20;

### Ownership Network & 92 Owners Feature

To keep everything in a single transaction for better performance, and not fragment the ownership pattern thus leading to a constant decrease in profits, we introduced the so-called “92 owners feature”. This feature acts like a recurrent network reset and ensures that a saNFT’s ownership network will not exceed the 92 owners.&#x20;

This means that when more than 92 users buy a saNFT, only the 92 users with the highest ownership percentage will be able to remain in the network and be rewarded for every new buyer.&#x20;

This feature also allows us to use at its best the stellar network (optimize the potentialities of the stellar network) by wrapping all layer-0 payments within one transaction. This also means that you have to choose carefully the percentage of ownership to acquire in order to stay longer in the network long enough to profit). But don’t worry, the [saNFT Analytics tool](sanft-analytics-tool.md) will help you make these decisions.&#x20;
