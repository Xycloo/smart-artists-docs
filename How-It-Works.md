---
order: 100
icon: beaker
---

<!--

### Artists Upload Their saNFTs

The Artists will be able to upload their <span style="font-size:1.3rem;color:#8C52FF">**saNFT**</span> to the marketplace. There currently is no dashboard as SmartArtists is still in development stage. 


If you wish to be one of the first Artists to be able to upload the first <span style="font-size:1.3rem;color:#8C52FF">**saNFTs**</span>, drop a message on my Twitter. I'll let you know when I'll be uploading the first beta NFTs.

<hr>

### Buying a saNFT

Users will then be able to aquire these assets for as much as they want through the Marketplace(<span style="color:#FFAF52">**buy offer**</span>, yes you can chose for how much you'll be buying a <span style="font-size:1rem;color:#8C52FF">**saNFT**</span>, you'll see why in the "How To Earn" page).

*The marketplace is currently under development, but soon the first beta <span style="font-size:1rem;color:#8C52FF">**saNFTs**</span> will be available on the production environment. To get the latest updates join the [Stellar Community Fund discord server](https://discord.gg/JYuczS2v).*

Users will be able to get <span style="font-size:1rem;color:#8C52FF">**saNFTs**</span> with either [Albedo](https://albedo.link/) or [XBull wallet](https://xbull.app/).

When a user buys a <span style="font-size:1rem;color:#8C52FF">**saNFT**</span>, they will become part of that <span style="font-size:1rem;color:#8C52FF">**saNFT**'s</span> network, and reward all the owners with their **buy offer** (this will be clearer once you read the "How to Earn" page). 

##### The How to Earn page will extend and explain the whole buy offer, and rewarding the owners concept.

-->

After reading this page, you will have an understanding of how Smartarists works. From the basics (how to earn, what you are buying, etc), to the more advanced features (pool accounts, unique nfts marketplace, reparations, etc). 

**Let's start!**
<hr>

## Basics


### What will you be buying?

> Pay attention here, this is one of the most confusing aspects of the project if you are used to buying standard NFTs.

When buying a smartartistsNFT (<span style="font-size:1rem;color:#8C52FF">**saNFT**</span>), you will mainly be doing 4 things:
1. [!badge Get the <span style="font-size:1rem;color:#8C52FF">**saNFT**</span> issued to your wallet](#get-the-sanft-issued-to-your-wallet).
2. [!badge Get a unique *"buyer NFT"* associated to your wallet](#get-a-unique-buyer-nft-associated-to-your-wallet).
3. [!badge Reward the Artist and the previous owners with your `buy_offer`](#rewarding).
4. [!badge Fund the pool account with a % of your `buy_offer`](#funding-the-pool-account).

Each of these 4 steps is a key part of the project in terms of dynamicity, and will be explain in detail in the next sections.

<hr>

### Get the saNFT issued to your wallet

<span style="font-size:1rem;color:#8C52FF">**saNFT**</span>s don't have a price, you can decide for how much XLM you want to buy them: that will be your *buy_offer*. What is the logic behind this? Let's find out!

When you get a saNFT issued to your wallet, the Stellar network will store on-chain the following information:

> *User* bought *testSaNFT* for a *buy_offer* of ***n*** XLM

This info will then be used to build an on-chain database of owners with how much each of them owns (their *buy_offer*) compared to the total of XLM that have been spent on that saNFT. 

For example, if a total of 900XLM have been spent on *testSaNFT*, and you bought it with a *buy_offer* of 100XLM, you would own 10% of *testSaNFT*'s ownership network as:
- total XLM on *testSaNFT* are 900 + your buy offer (100XLM) = 1000XLM
- you own 100XLM of 1000XLM, that's exactly the 10%

The more you own in the ownership network of a saNFT, the more you earn as you'll discover in the [Reward the Artist and the previous owners with your `buy_offer`]() section. **As you can see, the higher your *buy_offer* is, the more you'll possibly earn. That's why each buyer can decide their *buy_offer***.

<hr>

### Get a unique "buyer NFT" associated to your wallet

As you can understand, if the buyer can decide the price for the saNFT they're buying, there will be multiple owners for a single saNFT. This means that whenever a new user buys a new saNFT, they are buyer number `n`. When a user buys a saNFT, the platform will assign to their wallet a unique "*n*buyerNFT". 

That will be unique for your wallet, and will also become a source of profits for you in two different ways (see in the linked sections):
1. Marketplace
2. Artist's Rewards
> We are always working on new features, the ways to earn from this might even become more 😍

<hr>

### Rewarding
+++ Owners
The process of rewarding owners is quite simple and only requires basic maths to be understood. When you(user A) buy a saNFT, the platform will reward the previous owners with your *buy_offer*. 

Each owner gets rewarded differently, **depending on how much they own of the saNFT's ownership network** (if you don't know what this term is, give another read to the [first paragraph](#get-the-sanft-issued-to-your-wallet)).

But how much does each owner receive? This very simple formula covers it:

<img src="../ownearns.png"/>

>where:
>- buyOffer is your *buy_offer*
>- ownerdPerc is the percentage of the ownership network that the owner owns

##### The higher your *buy_offer*, the higher your owneedPerc, the more you'll earn for every new buyer.
+++ Artists
The process of rewarding artists is even simpler. Each time a new user buys the artist's saNFT, a fixed percentage (artist fee) of your *buy_offer* will go straight into the artist's wallet, while the remaining will go to reward the owners. 

It's obvious that the higher the higher the artist fee, the less owners will earn. So, how much in % is this artist fee?

It's decided by the artist themselves. This is what I liked about this platform when I started designing it: it allows artists to have a completely dynamic strategy planning (as you'll also see in the Advanced features section).

Anyways, doesn't this mean that the artist could set a fee of 99% and the owners would only receive 1%? Sure, but who's going to buy something that can profit them a maximum of 1%? **No one**. That's why the artist has to find a range of setting their fee that will also benefit the owners, so both the owners and the artist can profit.
+++
<hr>

### Funding the pool account

As you can see, an owner earns as long as there is always a new buyer ready to buy. While this is the principle behind trading standard NFTs, but I wanted something more for SmartArtists, I wanted a layer of dynamism which incentivizes new users to buy, by rewarding them.

#### How it works:

When a User buys a saNFT, a percentage of the *buy_offer* will be sent to a so-called **pool account** (a stellar account). The more buyers, the higher will be the value of this pool account.

Each **"tot time"** (*tot* stands for period, can *be each day, each  week, each month, etc; chosen by the artist*) this account will be equally divided between the *n* owners with the highest owned percentage of the latest *k* owners. (*the artist will set these two parameters*).

<details style="margin-bottom: 2vh">
<summary><strong>Who are the <i>k</i> owners?</strong></summary>
Latest <i>k</i> owners are the ones that have bought in a <i>k</i> period of time before <i>tot time</i>. For example, if <i>k</i> is 3 days and <i>tot time</i> is 1 month, the latest <i>k</i> owners will be the ones that have bought in the last 3 days.
</details>


This will ensure a high volume for that saNFT duing the *k* period, as there will be users **buying to get a part of the pool**. 

But there will also be buyers that buy before the *k* period trying to **anticipate big volumes**, as they know there will be more buyers next.

##### This will bring interesting developings, also from a purely trading-based perspective.