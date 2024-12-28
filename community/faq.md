# 📝 FAQ and Troubleshooting

Welcome to the **FAQ and Troubleshooting** page! Whether you’re a new player or a seasoned Pizza Pets pro, this resource aims to answer common questions and address potential issues. If your question isn’t covered here, feel free to submit your suggestions for new FAQs using the **Edit this page on GitHub** button.

***

## 🐾 Frequently Asked Questions

### **Q: What are Pizza Pets, and how do they work?**

Pizza Pets are **Tamagotchi-style digital pets** that evolve, require care, and interact with the Bitcoin blockchain. Players must manage their pets’ health, feeding, and evolution stages to keep them alive and thriving.

***

### **Q: How do I feed my pets?**

You can feed your pets using the available feeding sites:

* **Official Feeding Site**: [pizzapets.fun](https://www.pizzapets.fun/)
* [**@lifofifo**](https://x.com/lifofifo)**’s Feeding Site**: [pets.inscribe.dev](https://pets.inscribe.dev/)

**Watch the Video Guide 🎥**

If you'd like a step-by-step walkthrough of feeding mechanics, check out this video guide:

{% embed url="https://youtu.be/U3C5PlKuUGI?si=Fs9P0rM6Tr0--CfX" %}

***

### **Q: What is Game-Time, and How Does It Work?**

In **Pizza Pets**, _Game-Time_ is measured using **Bitcoin block counts** instead of real-world time, introducing a dynamic and decentralized timing mechanism. Here's how it works:

* **1 Game Hour** = **6 Bitcoin Blocks** (\~1 hour)
* **1 Game Day** = **144 Bitcoin Blocks** (\~1 day)
* **1 Game Week** = **1,008 Bitcoin Blocks** (\~1 week)

{% hint style="info" %}
Time estimates assume an average of 10 minutes per Bitcoin block. However, actual block times can vary due to network conditions. This means a "game hour" might take 30 minutes or several hours, making _Game-Time_ more **dynamic and unpredictable** compared to fixed real-world time.
{% endhint %}

This variability adds an exciting element of spontaneity and unpredictability to the gameplay experience.

For more, visit: [Game-Time Explained](../resources/timeline-and-seasons.md#understanding-game-time)

***

### **Q: Why does the game use Bitcoin blocks instead of real time?**

Using Bitcoin blocks ensures a **decentralized, dynamic experience**. Unlike fixed clocks, block times vary, creating unpredictability in gameplay. It’s part of the challenge—and the fun!

***

### **Q: How many pets are alive, dead, and in circulation?**

The current statistics for **alive pets**, **dead pets**, and the **total number of pets in circulation** are updated live and can be viewed at the [Pizza Pets Dashboard](https://www.pizzapets.fun/dashboard).

***

### **Q: How does the deflationary mechanic work?**

When a pet dies, it is **permanently removed** from the collection, reducing the overall supply. This deflationary effect increases the rarity of surviving pets, impacting their value in the ecosystem. See more in the dedicated page:

{% content-ref url="../advanced-strategies/deflationary-effect.md" %}
[deflationary-effect.md](../advanced-strategies/deflationary-effect.md)
{% endcontent-ref %}

***

### **Q: What happens if my pet poops and I don’t clean it?**

Uncleaned poop increases your pet’s **heart loss rate** from 1 heart per day to **1.4 hearts per day per poop**. Multiple poops can stack, leading to faster heart loss. Use a **Shower** to clean poop and reset the heart loss rate to normal. See details in:

[Evolution Stages](../game-mechanics/poop-management.md#the-consequences-of-poop)

***

### **Q: Can I feed Cocaine and Steroids in one transaction?**

🚫 No! Certain items, like **Cocaine** and **Steroids**, cannot be combined in a single transaction. Both feeding sites have safeguards to prevent this:

* **Official Feeding Site**: [pizzapets.fun](https://www.pizzapets.fun/)
* [**@lifofifo**](https://x.com/lifofifo)**’s Feeding Site**: [pets.inscribe.dev](https://pets.inscribe.dev/)

To achieve the best results, **feed Cocaine first**, followed by Steroids in a separate transaction. Just remember: this isn’t the **Ninja Turtle Power Combo** you might think it is—use responsibly!

***

### **Q: Can I feed Steroids multiple times to increase evolution rates?**

🚫 No! **Steroids do not stack**. Feeding them multiple times will only waste your extra transactions (and potentially your pet’s patience). This is more like trying to double-spend on Bitcoin—it won’t work.

***

### **Q: Can I bring a dead pet back to life?**

No. Once a pet dies, it is permanently removed from the collection. The deflationary nature of the game is core to its design.

***

### **Q: How do I protect my pets from the Pet Pulverizer?**

Apply **Lotion** to pets that match the Pulverizer’s type (e.g., Yellow Pineapple Weakness) to protect them. Pets with **Immune traits**, as well as those in the Egg, Baby, or Immortal stages, are naturally safe. See more in:

{% content-ref url="../game-mechanics/pet-pulverizer.md" %}
[pet-pulverizer.md](../game-mechanics/pet-pulverizer.md)
{% endcontent-ref %}

***

### **Q: How do I use Milk to counteract drug effects?**

Milk removes all active drug effects:

* Feed Milk before the specified block deadline for drugs like **Cocaine** or **LSD** to prevent fatal outcomes.
* For other drugs like **Steroids** or **Coffee**, Milk can be used anytime to reset effects. See more in:

{% content-ref url="../game-mechanics/game-actions.md" %}
[game-actions.md](../game-mechanics/game-actions.md)
{% endcontent-ref %}

***

### **Q: My pet died because I missed the Milk block deadline. What can I do?**

Unfortunately, there is no way to recover a dead pet. Set alarms or reminders for critical block deadlines to avoid missing them in the future. Tools like [Mind Your Milk](https://www.mindyourmilk.pizza/) by [@0xBGoat](https://x.com/0xBGoat) can help you set reminders to avoid this mistake.

***

### **Q: My pets disappeared after I submitted a feed or game action transaction. Where did they go?**

The feed and game actions are an **ordinal inscription**, which requires a **commit** and **reveal** transaction. During this stage, the feeding sites will show your pets in the mempool. Once the transaction is confirmed, the pets will return to your account.

If you experience issues, reach out to the Ninjalerts team on Discord for support: [discord.com/invite/pizzaninjas](https://discord.com/invite/pizzaninjas).

***

### **Q: If my pet is on a drug that has a kill or death block such as Cocaine, LSD, etc., can I just feed it the same drug again before the death block arrives to extend the death block further?**

**A:**\
No, you cannot extend the death block by feeding the same drug again. To apply a new death block:

1. **Feed Milk** to remove the existing drug effect and its associated death block.
2. Then, **feed the drug again** to create a new effect and establish a new death block.

Ralf might argue this is part of Ninjalerts’ grand scheme to limit your pets’ potential, but we know the real story: it’s all about strategy! Timing is everything—just like planning your next Bitcoin transaction in a congested mempool.

***

### **Q: Can I give my pet a Shower in the same block poop is incoming?**

**A:**\
No, it will waste the Shower. The poop block needs to **confirm first** before the Shower is applied. Attempting to Shower in the same block will have no effect because the game mechanics require the poop status to be fully confirmed on-chain.

Think of it as waiting for your Bitcoin transaction to finalize before calling it “confirmed.” Ralf might say Ninjalerts made the rules to keep him busy cleaning up moon cheese crumbs, but Pizza Ninjas know it’s just the game’s way of keeping us sharp.

***

### **Q: Can I feed my pet in the same block it’s projected to die to save the pet?**

**A:**\
Yes, but it’s risky. If your feed or Milk transaction confirms **in the same block as the pet’s death block**, it will save the pet. This applies to:

* Pets dying due to heart health loss.
* Pets on drugs like Cocaine or LSD with a death block.

However, this requires precise timing, as the transaction must be confirmed **within the same block**. Ralf might call this high-stakes gambling (and he’d be right), but Bitcoiners know it’s all about precision and mempool management. Channel your inner Pizza Ninja and aim for perfect timing!

***

## 🌟 Need More Help?

For additional support:

* **Official Feeding Site**: [pizzapets.fun](https://www.pizzapets.fun/)
* **@lifofifo’s Feeding Site**: [pets.inscribe.dev](https://pets.inscribe.dev/)
* **Milk Reminder Tool**: [Mind Your Milk](https://www.mindyourmilk.pizza/)

If you need further assistance:

* Join the **Ninjalerts Discord** for community support: [discord.com/invite/pizzaninjas](https://discord.com/invite/pizzaninjas).
* Please note: Reaching out to me directly won’t be efficient as I’m just a volunteer community member.

***

## 💡 Suggest an FAQ

If you have suggestions for additional FAQs or troubleshooting topics, click the **Edit this page on GitHub** button at the top of this page and submit your request. Your input helps make this guide better for everyone! 🍕🐾
