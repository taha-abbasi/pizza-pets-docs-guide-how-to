# 🧠 Advanced Strategies

Welcome to the **Advanced Strategies** section, where we delve into creative and high-risk gameplay techniques to optimize your Pizza Pets experience. These strategies often involve **PEDs**, **SADs**, and other game mechanics that require precise planning and timing. Remember, the key to success is balancing risk and reward!

This page will evolve as new strategies are discovered and shared. Stay tuned for updates!

***

## 🚀 Strategy: Evolve Faster Without Heart Loss or Poop

### **Overview**

This strategy leverages **Cocaine** and **Steroids** to speed up evolution while preventing heart loss for a limited time. However, it comes with significant risks and costs, requiring careful monitoring of block times to avoid losing your pet.

***

### **How It Works**

* **Risk Level**: ⭐⭐⭐⭐ (4/5)
* **Reward Level**: ⭐⭐ (2/5)

By combining **Cocaine** and **Steroids**, you can temporarily bypass heart loss while increasing evolution speed by 1.5x. The trade-offs include:

* The pet will die in **432 blocks (\~3 days)** after Cocaine unless fed **Milk**.
* Feeding Milk also removes the Steroids effect, so the cycle must be repeated.

***

### **Transaction Cycle**

1. **Feed Cocaine**: Stops heart loss for 432 blocks.
2. **Feed Steroids**: Speeds up evolution by 1.5x.
3. **Feed Milk (\~400 blocks after Cocaine)**: Must be done before 432 blocks to save the pet.

#### Repeat the Cycle:

Cocaine → Steroids → Milk.\
This reduces evolution time by 1/3rd compared to default gameplay but is costly in terms of resources and transactions.

***

## **Cost Analysis**

This strategy requires more resources than the standard process of feeding **Pizza** or **Beer** and occasionally using **Shower**. It’s best suited for players aiming to expedite evolution in high-stakes scenarios.

### Cost Summary for MCS (Milk + Cocaine + Steroids) Strategy&#x20;

{% hint style="info" %}
The data is organized in tabs by feeding sites and access levels
{% endhint %}

#### Immortal Evolution Cost For 1 Pet

{% tabs %}
{% tab title="Pizza Pets" %}
| **Stage**         | **Blocks Needed (1.5x Faster)** | **Feeds Needed** | **Feed Cycle Cost (sats)** | **Total Cost (BTC)** | **Total Cost (USD)** |
| ----------------- | ------------------------------- | ---------------- | -------------------------- | -------------------- | -------------------- |
| Baby to Immortal  | 6,720                           | 17               | 18,393                     | 0.00311924           | 296.29               |
| Child to Immortal | 6,048                           | 16               | 18,393                     | 0.00309478           | 293.04               |
| Teen to Immortal  | 4,704                           | 12               | 18,393                     | 0.00233315           | 220.72               |
| Adult to Immortal | 2,688                           | 7                | 18,393                     | 0.00136121           | 128.75               |
{% endtab %}
{% tab title="Lifo Inscribe_Dev" %}

{% endtab %}

{% tab title="Lifo Inscribe_Dev w 10 Wiz" %}

{% endtab %}
{% endtabs %}



#### Immortal Evolution Cost For 11 Pets

{% tabs %}
{% tab title="Pizza Pets" %}
| **Stage**         | **Blocks Needed (1.5x Faster)** | **Feeds Needed** | **Feed Cycle Cost (sats)** | **Total Cost (BTC)** | **Total Cost (USD)** |
| ----------------- | ------------------------------- | ---------------- | -------------------------- | -------------------- | -------------------- |
| Baby to Immortal  | 6,720                           | 17               | 61,743                     | 0.01090549           | 994.04               |
| Child to Immortal | 6,048                           | 16               | 61,743                     | 0.01073498           | 935.52               |
| Teen to Immortal  | 4,704                           | 12               | 61,743                     | 0.00805762           | 701.64               |
| Adult to Immortal | 2,688                           | 7                | 61,743                     | 0.00432322           | 409.29               |
{% endtab %}
{% tab title="Lifo Inscribe_Dev" %}

{% endtab %}

{% tab title="Lifo Inscribe_Dev w 10 Wiz" %}

{% endtab %}
{% endtabs %}
***

### Key Points

1. **Cost Efficiency for More Pets**\
   Feeding more pets in a single transaction significantly reduces the per-pet cost. For example:
   * **1 Pet Feed Transaction**: Costs **6,131 sats**.
   * **11 Pets Feed Transaction**: Costs **20,581 sats**, reducing the per-pet cost to **1,871 sats**.
2. **Scaling Costs**\
   Feeding strategies become more cost-efficient as the number of pets fed per transaction increases. This can save players significant resources over multiple feed cycles.
3. **Total Costs for Different Stages**\
   Use the tables above to compare costs for evolving 1 pet versus 11 pets across different stages.

> For detailed calculations, refer to the [Cost Formula Reference](advanced-strategies.md#cost-formula-reference).

***

## 🌀 Strategy: DMT Your Way to 11 Immortals

### **Overview**

Coming soon.

***

## 🐎 Strategy: Ketamine and DMT

### **Overview**

Coming soon.

***

## 🍄 Strategy: Psychedelic Bliss for Pizza Pets

### **Overview**

Coming soon.

***

## **Cost Formula Reference**

This section explains the standard formulas used to calculate feeding costs, block cycles, and other game mechanics.

### Formula 1: TotalFeedsNeeded

$$TotalFeedsNeeded = ⌈ TotalBlocks / BlocksPerFeedCycle ⌉$$

### Formula 2: CostPerCycle (sats)

$$CostPerCycle (sats) = CostPerTransaction (sats) × NumberOfTransactionsPerCycle$$

### Formula 3: CostPerCycle (USD)

$$CostPerCycle (USD) = (CostPerCycle (sats) / BtcPriceInSats) × 100,000,000$$

### Formula 4: TotalCost (USD)

$$TotalCost (USD) = CostPerCycle (USD) × TotalFeedsNeeded$$

### Formula 5: TotalCost (BTC)

$$TotalCost (BTC) = TotalCost (sats) / 100,000,000$$

### Parameters

* **BtcPriceInSats** = $$BTC Price in USD × 100,000,000$$
* **Fee Rate** = The rate in sats/vByte used for transactions.

***

### Detailed Breakdown for MCS Strategy

#### Step 1: Determining the Number of Feeding Cycles

**Formula**:\
$$TotalFeedsNeeded = ⌈ TotalBlocks / BlocksPerFeedCycle ⌉$$

* **Baby to Immortal**:\
  $$TotalFeedsNeeded = ⌈ 6,720 / 400 ⌉ = 17$$
* **Child to Immortal**:\
  $$TotalFeedsNeeded = ⌈ 6,048 / 400 ⌉ = 16$$
* **Teen to Immortal**:\
  $$TotalFeedsNeeded = ⌈ 4,704 / 400 ⌉ = 12$$
* **Adult to Immortal**:\
  $$TotalFeedsNeeded = ⌈ 2,688 / 400 ⌉ = 7$$

#### Step 2: Cost per Feeding Cycle

Each feed cycle involves **3 transactions** (Milk, Cocaine, and Steroids):

**Formula**:

* For **11 Pets**:\
  $$CostPerCycle (sats) = 20,581 × 3 = 61,743 \, \text{sats}$$
* For **1 Pet**:\
  $$CostPerCycle (sats) = 6,131 × 3 = 18,393 \, \text{sats}$$

#### Step 3: Total Cost for Immortal Evolution

**Formula**:\
$$TotalCost (USD) = CostPerCycle (USD) × TotalFeedsNeeded$$

* **11 Pets - Baby to Immortal**:\
  $$TotalCost (USD) = 58.47 × 17 = 994.04 \, \text{USD}$$
* **1 Pet - Baby to Immortal**:\
  $$TotalCost (USD) = 17.45 × 17 = 296.29 \, \text{USD}$$

***

## Support and Donations 💖

If this guide helps you, consider supporting us! Donations cover hosting costs and keep our content fresh and relevant. Your generosity powers the continued evolution of Pizza Pets and ensures this guide stays awesome. Details can be found on the donations page.

{% content-ref url="resources/donations.md" %}
[donations.md](resources/donations.md)
{% endcontent-ref %}

***

## 🐾 More Strategies Coming Soon

This page is a work in progress! We’ll continue to add advanced strategies to help you master the game. If you have a creative strategy or insight to share, consider submitting your ideas via GitHub or joining the discussion on Discord.

Stay tuned as we unlock the full potential of Pizza Pets! 🍕🐾