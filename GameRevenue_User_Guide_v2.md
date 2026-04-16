# GameRevenue.ai — User Guide
*Free Steam pricing and discount planning tools for indie developers*

---

## What Is GameRevenue.ai?

GameRevenue.ai gives indie developers two free tools to make smarter Steam pricing and discount decisions:

- **MSRP Intelligence Tool** — See what comparable games charge across 40+ Steam markets and get regional price recommendations
- **Steam Discount Planner** — Plan your 2026 discount calendar around Steam's promotional events without triggering cooldown conflicts

No account required to use the tools. No connection to your Steamworks account.

---

## Tool 1: MSRP Intelligence Tool

### What It Does
Pulls current Steam prices for a set of comparable games across 40+ countries, then recommends regional prices for your game based on what the market actually charges — with vanity pricing built in.

### Step-by-Step

**Step 1 — Enter your USD price**
Type your intended US launch price. Use $10 increments (e.g. $14.99, $19.99, $24.99).

**Step 2 — Build your competitive set**
Select from built-in presets (Indie Tier, AA Tier, AAA Tier) or search for specific games by name. Aim for 3–6 titles that are genuinely comparable to yours in genre, scope, and audience.

**Step 3 — Pull prices**
Click "Get Prices." The tool fetches live Steam store prices for every game in your set across all markets.

**Step 4 — Review the output**
You'll see a table showing:
- What each comp charges per country
- The recommended price for your game in each market
- VAT impact by country
- Any price alerts (markets where pricing looks unusual)

**Step 5 — Export**
Download the recommendations as a CSV to use when setting prices in Steamworks.

### Understanding Vanity Pricing
Every currency has conventions for what "looks right" to local buyers. $19.99 works in USD. ¥2,000 works in JPY. ₩19,800 works in KRW. The tool applies these conventions automatically so your prices don't look like a math error in any market.

### Price Alerts
A warning appears when a market's recommended price is significantly below the USD equivalent. This usually means competitors haven't updated prices after currency depreciation. You may want to price higher in these markets.

---

## Tool 2: Steam Discount Planner

### What It Does
Maps your game's launch date against the full 2026 Steam promotional calendar — including all four tentpole sales, 17+ themed fests, and Early Access windows — and builds a recommended discount schedule that avoids cooldown conflicts.

### Key Concepts Before You Start

**The 30-Day Cooldown Rule**
After running a sale on Steam, you cannot run another sale on the same SKU for 30 days. Violating this locks you out of upcoming events. The planner flags these conflicts automatically.

**Tentpole Sales Are Exempt**
Steam's four major sales (Spring, Summer, Autumn, Winter) are exempt from the 30-day cooldown. You can participate in a tentpole even if you ran a custom sale recently. The planner accounts for this.

**Early Access Sales**
Steam auto-generates Early Access sale opportunities before tentpoles (Spring, Summer, Autumn). These are valuable for building momentum. Note: Early Access sales are NOT tentpole-exempt — they trigger cooldowns. The planner flags this so you don't accidentally block yourself.

**Custom Sales**
Any sale you run outside of Steam's official calendar (timed to a game update, DLC launch, or in-game event). These trigger cooldowns and must be planned carefully.

### Step-by-Step

**Step 1 — Enter your launch date**
Select the date you plan to launch on Steam.

**Step 2 — Set your discount preferences**
Choose your discount range (e.g. 10%–50%) and cadence preference (Conservative = 4–6 sales/year, Aggressive = 8–10+ sales/year).

**Step 3 — Review the recommended calendar**
The planner outputs a suggested discount schedule showing:
- Which tentpole sales to participate in
- Which fests are relevant to your genre
- Where to slot custom sales without triggering conflicts
- Cooldown warnings if anything overlaps

**Step 4 — Add custom events**
Use "Add Custom Event" to plan sales around your specific game milestones (patch launches, DLC, anniversaries).

**Step 5 — Export**
Download your discount calendar as a CSV.

### Discount Depth Strategy
Industry data suggests a stairstep approach works best:
- First sale: 10–20%
- Second sale: 25–33%
- Later sales: 40–50%
- Deep discounts (50%+): Best suited for major tentpole sales or when velocity has slowed and you need to re-engage the market — timing depends on your game's performance, not a fixed post-launch window

Going too deep too early trains players to wait for sales and anchors expectations. That said, if sales have stalled, a deeper discount paired with a tentpole or content update is a legitimate tool — use it when the data tells you to, not on a fixed schedule.

---

## Frequently Asked Questions

**Q: Is this affiliated with Steam or Valve?**
A: No. GameRevenue.ai is an independent tool using publicly available Steam store data.

**Q: Where does the pricing data come from?**
A: Live Steam store pages. The tool fetches current prices for each game in your competitive set.

**Q: Why do some countries show price alerts?**
A: The alert appears when a market's recommended price is significantly below the USD equivalent. This usually means competitors haven't updated after currency depreciation. Consider whether to price higher in those markets.

**Q: Can I save my competitive set?**
A: Your custom additions persist during your session but reset when you close the browser. Export your recommendations to save them.

**Q: How accurate are the revenue uplift estimates?**
A: They're based on industry averages and should be treated as directional estimates, not guarantees. Results depend on your game's visibility, quality, and audience.

**Q: What if I want to run a sale not on the calendar?**
A: Use the "Add Custom Event" feature. The planner will flag any cooldown conflicts.

**Q: Can I participate in every tentpole sale?**
A: Yes — tentpoles are exempt from the 30-day cooldown. That said, consider whether frequent discounting fits your pricing strategy long-term.

**Q: Is my data secure?**
A: Your optional registration info (name, email) is stored securely. We have no access to your Steamworks account or sales data.

**Q: Is this really free?**
A: Yes. We're in an early validation phase and want honest feedback from real developers. Core Steam tools will remain free.

**Q: How do I report a bug or request a feature?**
A: Email admin@gamerevenue.ai — we read everything.

---

## Tips for Success

1. **Pick comps honestly** — games that are genuinely similar to yours, not aspirational titles. Better comps = better recommendations.
2. **Don't discount too deep too early** — you can always go deeper, you can't go back up without damaging trust.
3. **Pair custom sales with content** — a sale alongside a major patch or DLC performs significantly better than a standalone discount.
4. **Participate in relevant fests** — they're free visibility on top of the discount.
5. **Check pricing after major currency moves** — regional pricing can drift significantly after exchange rate shifts.
6. **Export everything** — use the CSVs as a working document when setting prices in Steamworks.

---

## Support

Questions, bugs, or feedback: **admin@gamerevenue.ai**

*Last Updated: April 2026*
