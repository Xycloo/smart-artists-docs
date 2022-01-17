# Formulas

#### Network Slice of an Owner

$$
OwnerNetworkSlice = \frac{ownerBuyOffer * 100}{totalXLM}
$$

#### Owner Earns (in XLM)

$$
OwnerEarns = \frac{(newUserBuyOffer -mixedFee ) * OwnerNetworkSlice}{100}
$$

#### Mixed Fee

The mixedFee is a portion of the buy\_offer and is divided into two fees:

* `artistFee`: goes directly into the artist's wallet (without fees).
* `poolFee`: used for [funding Layer-1](../learn/volume-pools-layer-1.md#funding-the-pool).

