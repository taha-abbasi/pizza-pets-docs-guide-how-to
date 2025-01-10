# 🧠 Advanced Strategies

Welcome to the **Advanced Strategies** section, where we delve into creative and high-risk gameplay techniques to optimize your Pizza Pets experience. These strategies often involve **PEDs**, **SADs**, and other game mechanics that require precise planning and timing. Remember, the key to success is balancing risk and reward!

This page will evolve as new strategies are discovered and shared. Stay tuned for updates!

---

## 🚀 Strategy: Evolve Faster Without Heart Loss or Poop

### **Overview**

This strategy leverages **Cocaine** and **Steroids** to speed up evolution while preventing heart loss for a limited time. However, it comes with significant risks and costs, requiring careful monitoring of block times to avoid losing your pet.

---

### **How It Works**

- **Risk Level**: ⭐⭐⭐⭐ (4/5)  
- **Reward Level**: ⭐⭐ (2/5)

By combining **Cocaine** and **Steroids**, you can temporarily bypass heart loss while increasing evolution speed by 1.5x. The trade-offs include:

- The pet will die in **432 blocks (\~3 days)** after Cocaine unless fed **Milk**.
- Feeding Milk also removes the Steroids effect, so the cycle must be repeated.

---

### **Transaction Cycle**

1. **Feed Cocaine**: Stops heart loss for 432 blocks.
2. **Feed Steroids**: Speeds up evolution by 1.5x.
3. **Feed Milk (\~400 blocks after Cocaine)**: Must be done before 432 blocks to save the pet.

#### Repeat the Cycle:
Cocaine → Steroids → Milk.  
This reduces evolution time by 1/3rd compared to default gameplay but is costly in terms of resources and transactions.

---

## **Cost Analysis**

This strategy requires more resources than the standard process of feeding **Pizza** or **Beer** and occasionally using **Shower**. It’s best suited for players aiming to expedite evolution in high-stakes scenarios.

### Cost Summary for MCS (Milk + Cocaine + Steroids) Strategy (11 Pets)

| **Stage**         | **Blocks Needed (1.5x Faster)** | **Feeds Needed** | **Feed Cycle Cost (sats)** | **Total Cost (USD)** |
|--------------------|---------------------------------|------------------|----------------------------|----------------------|
| Baby to Immortal   | 6,720                          | 17               | 61,743                     | 994.04              |
| Child to Immortal  | 6,048                          | 16               | 61,743                     | 935.52              |
| Teen to Immortal   | 4,704                          | 12               | 61,743                     | 701.64              |
| Adult to Immortal  | 2,688                          | 7                | 61,743                     | 409.29              |

> For detailed calculations, refer to the [Cost Formula Reference](#cost-formula-reference).

---

## 🌀 Strategy: DMT Your Way to 11 Immortals

Coming soon.

---

## 🐎 Strategy: Ketamine and DMT

Coming soon.

---

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

### Parameters
- **BtcPriceInSats** = $$BTC Price in USD × 100,000,000$$
- **Fee Rate** = The rate in sats/vByte used for transactions.

---

### Detailed Breakdown for MCS Strategy

#### Step 1: Determining the Number of Feeding Cycles

**Formula**:  
$$TotalFeedsNeeded = ⌈ TotalBlocks / BlocksPerFeedCycle ⌉$$

- **Baby to Immortal**:  
  $$TotalFeedsNeeded = ⌈ 6,720 / 400 ⌉ = 17$$

- **Child to Immortal**:  
  $$TotalFeedsNeeded = ⌈ 6,048 / 400 ⌉ = 16$$

- **Teen to Immortal**:  
  $$TotalFeedsNeeded = ⌈ 4,704 / 400 ⌉ = 12$$

- **Adult to Immortal**:  
  $$TotalFeedsNeeded = ⌈ 2,688 / 400 ⌉ = 7$$

#### Step 2: Cost per Feeding Cycle

Each feed cycle involves **3 transactions** (Milk, Cocaine, and Steroids) to feed **11 pets**:

**Formula**:  
$$CostPerCycle (sats) = 20,581 × 3 = 61,743 \, \text{sats}$$

At the current Bitcoin price of **$94,700**, the dollar value for one cycle is:

1. **BtcPriceInSats**:  
   $$BtcPriceInSats = 94,700 × 100,000,000 = 9,470,000,000,000 \, \text{sats}$$

2. **CostPerCycle (USD)**:  
   $$CostPerCycle (USD) = (61,743 / 9,470,000,000,000) × 100,000,000 = 58.47 \, \text{USD}$$

#### Step 3: Total Cost for Immortal Evolution

**Formula**:  
$$TotalCost (USD) = CostPerCycle (USD) × TotalFeedsNeeded$$

- **Baby to Immortal**:  
  $$TotalCost (USD) = 58.47 × 17 = 994.04 \, \text{USD}$$

- **Child to Immortal**:  
  $$TotalCost (USD) = 58.47 × 16 = 935.52 \, \text{USD}$$

- **Teen to Immortal**:  
  $$TotalCost (USD) = 58.47 × 12 = 701.64 \, \text{USD}$$

- **Adult to Immortal**:  
  $$TotalCost (USD) = 58.47 × 7 = 409.29 \, \text{USD}$$

---

## Support and Donations 💖

If this guide helps you, consider supporting us! Donations cover hosting costs and keep our content fresh and relevant. Your generosity powers the continued evolution of Pizza Pets and ensures this guide stays awesome. Details can be found on the donations page.

{% content-ref url="resources/donations.md" %}
[donations.md](resources/donations.md)
{% endcontent-ref %}

---

## 🐾 More Strategies Coming Soon

This page is a work in progress! We’ll continue to add advanced strategies to help you master the game. If you have a creative strategy or insight to share, consider submitting your ideas via GitHub or joining the discussion on Discord.

Stay tuned as we unlock the full potential of Pizza Pets! 🍕🐾