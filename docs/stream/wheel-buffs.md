# Ms Bacon's Code Wheel & Active Buffs

Ms Bacon's Code Wheel is a 60fps physics-driven prize wheel featured live on the stream overlay. Viewers can trigger wheel spins by redeeming live 2FA secret codes or hidden Shorts codes.

---

## 🥓 Ms Bacon's Secret Codes

During the 24/7 live stream, **Ms Bacon's Secret Codes** appear dynamically under the counter widget accompanied by a golden notification and piano chime:

- Codes are **6-digit TOTP security codes** that refresh every 30 seconds.
- Each code can only be redeemed **once** by the fastest viewer in chat!
- Claim the code in chat using:
  `
  !code 123456
  `
  or
  `
  !c 123456
  `
- The first viewer to claim spins the live Prize Wheel on stream.

---

## 🎰 Wheel Prize Tiers

The prize wheel features custom Minecraft-style beveled cards with distinct rarity colors and audio effects:

| Prize Tier | Reward | Rarity / Details |
| :--- | :--- | :--- |
| **🎰 Mega Jackpot** | **5,000,000 Hoob Loot** | 5% Chance (Golden Jackpot theme) |
| **💎 Grand Jackpot** | **1,000,000 Hoob Loot** | 15% Chance (Purple Rank theme) |
| **🪙 High Loot** | **500,000 Hoob Loot** | 20% Chance (Dark Red theme) |
| **🪙 Mid Loot** | **250,000 Hoob Loot** | 20% Chance (Red theme) |
| **🪙 Standard Loot**| **100,000 Hoob Loot** | 15% Chance (Dark Aqua theme) |
| **🪙 Low Loot** | **50,000 Hoob Loot** | 10% Chance (Aqua theme) |
| **🪙 Troll Prize** | **1 Hoob Loot** | 5% Chance (Dark theme) |
| **⚡ 2X Loot Multiplier** | **10 Minutes 2X Buff** | 5% Rare Perk (Gold theme) |
| **🏷️ 50% OFF Shop Coupon** | **1-Use 50% Discount** | 5% Rare Perk (Aqua theme) |

> **Anti-Spoiler Queue Delay**: The bot delays announcing the chat result by ~22 seconds so live stream buffering won't spoil the wheel landing before viewers see it on stream! If multiple viewers claim codes close together, a FIFO queue badge displays their position.

---

## ⚡ Active Perks & Multipliers

### 1. ⚡ 2X Loot Multiplier
- Doubles **all Hoob Loot** earned from chat commands (!free, !bacon, !daily, !weekly, !monthly, raffles).
- Multiple multiplier wins **stack additively** (e.g., winning two 10-minute buffs gives 20 total minutes).
- Check your remaining time using:
  `
  !coupons
  `
  or !buffs, !perks, !discount.

### 2. 🎟️ 50% OFF Shop Coupons
- Automatically cuts the Hoob Loot price of your next !shop purchase in half!
- Stored as individual charges on your viewer account.
- When purchasing an item in !shop, 1 coupon is automatically consumed and you pay 50% off.

---

## 💌 Gifting Perks to Other Viewers (!give)

Viewers can gift loot, transfer their active 2X multiplier time, or transfer unused shop coupons to any other viewer in chat!

### Command Examples:

- **Transfer 2X Loot Multiplier**:
  `
  !give <viewer> 2x
  `
  Transfers all of your remaining 2X multiplier time to <viewer>.
  `
  !give <viewer> 2x 5m
  `
  Transfers up to 5 minutes of your 2X multiplier.

- **Transfer 50% OFF Shop Coupons**:
  `
  !give <viewer> coupon
  `
  Transfers 1x 50% OFF shop coupon to <viewer> (also accepts !give <viewer> 50%).
  `
  !give <viewer> coupon 2
  `
  Transfers 2 coupons to <viewer> (also accepts !give <viewer> 2 coupons).

- **Transfer All Active Perks**:
  `
  !give <viewer> buffs
  `
  Transfers both your active 2X multiplier time AND all your unused 50% OFF coupons in a single gift!

- **Gift Hoob Loot**:
  `
  !give <viewer> 50000
  `
  Transfers 50,000 Hoob Loot to <viewer> (subject to daily receive limit of 1,000,000 loot).

> **Real-Time App Sync**: Whenever you give or receive a perk, both players' [Companion Apps](https://app.hoobs.live) update instantly with their new active buffs!
