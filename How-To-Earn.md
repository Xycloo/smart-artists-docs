---
order: 99
icon: ruby
---

When you buy a <span style="font-size:1rem;color:#8C52FF">**saNFT**</span> you will be doing two things:

#### 1. Enter the Network
Based on your <span style="color:#FFAF52">**buy offer**</span> and the total XLM that have been spent on that <span style="font-size:1rem;color:#8C52FF">**saNFT**</span>, you will own a percentage of the network that <span style="font-size:1rem;color:#8C52FF">**saNFT**</span>.

This percentage will be calculated with the following formula:
<img src="../ownperc.png"/>

#### 2. Reward Owners
Your buy offer will be divided between the all owners of that <span style="font-size:1rem;color:#8C52FF">**saNFT**</span>. Each owner will receive a percentage of your <span style="color:#FFAF52">**buy offer**</span> based on their owned percentage of the network:
<img src="../ownearns.png"/>


##### The higher your <span style="color:#FFAF52">**buy offer**</span>, the more you own the <span style="font-size:1rem;color:#8C52FF">**saNFT**</span> network, the more you earn.

<hr>

### Volume/Reward Pools

As you can see, an owner earns as long as there is always a new buyer ready to buy. While this is the principle behind trading standard NFTs, I wanted something more for SmartArtists, that's because, as you already know, these are not standard NFTs.

Using the volume/rewards pools functionality, I added a layer of dynamicism to the platform, incentivizing users to buy.

#### How it works:

When a User buys a saNFT, a percentage of how much the artist earns will be sent to a so-called **pool account** (a stellar account). The more buyers, the higher will be the value of this pool account.

Each **"tot time"** (*tot* stands for period, can *be each day, each  week, each month, etc; chosen by the artist*) this account will be equally divided between the *n* owners with the highest owned percentage of the latest *k* owners. (*the artist will set these two parameters*).

<details style="margin-bottom: 2vh">
<summary><strong>Who are the <i>k</i> owners?</strong></summary>
Latest <i>k</i> owners are the ones that have bought in a <i>k</i> period of time before <i>tot time</i>. For example, if <i>k</i> is 3 days and <i>tot time</i> is 1 month, the latest 3 owners will be the ones that have bought in the last 3 days.
</details>


This will ensure a high volume for that NFT before the **"tot time"** is about to end, as there will be users **buying to get a part of the pool**. But there will also be buyers trying to **anticipate the big volume period**, as they know there will be a lot of buyers.

##### This will bring interesting developings, also from a trading perspective: read more in the next page.