# Layer-0



Layer-0 is the core mechanism behind saNFTs, learning this concept ensures an in-depth understanding of the basic dynamics of a saNFT.

#### What actually happens when you buy a saNFT?

1. You buy a slice of the saNFT’s ownership network, thus becoming part of the network itself. The size of your slice in the network depends on your buy offer, that’s why you will choose how much to invest in a saNFT. Your slice will be calculated in percentages with the following formula: (owner\_buy\_offer \* 100) / total\_xlm, where total\_xlm is the all-time amount of lumens that have been spent on that saNFT.&#x20;
2. Each time a new buyer steps in, their buy offer will be distributed between all the owners according to their percentage of ownership. It goes without saying that every time a new owner steps into the network, these percentages (after the new owner’s buy offer is distributed) will be adjusted as there will be more total\_xlm and more owners.&#x20;
3. It’s important to say that a percentage of the buy offer will go straight to power the LAYER-1 earning mechanism.&#x20;
4. All of this, while a percentage of the buy\_offer will go straight into the artists’ wallet with no fees taken by smart artists.&#x20;

To keep everything in a single transaction for better performance, and not fragment the ownership pattern thus leading to a constant decrease in profits, we introduced the so-called “92 owners feature”. This feature acts like a recurrent network reset and ensures that a saNFT’s ownership network will not exceed the 92 owners.&#x20;

This means that when more than 92 users buy a saNFT, only the 92 users with the highest ownership percentage will be able to remain in the network and be rewarded for every new buyer.&#x20;

This feature also allows us to use at its best the stellar network (optimize the potentialities of the stellar network) by wrapping all layer-0 payments within one transaction. This also means that you have to choose carefully the percentage of ownership to acquire in order to stay longer in the network long enough to profit). But don’t worry, the [saNFT Analytics tool](sanft-analytics-tool.md) will help you make these decisions.&#x20;
