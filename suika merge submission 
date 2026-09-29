# Suika Merge

Drop fruit into the jar with your Rare Friend, merge matching fruit up the tiers, and cash out your multiplier before the jar overflows.

**Builder:** Dapper / [@F17UK](https://x.com/F17UK) · **Category:** Economy Potential · **SDK:** FriendSDK v0.1.2

[Source code](https://github.com/DapperDutchDude/rarefriends-vibeathon/tree/main/submissions/suika-merge) · [Game rules](https://github.com/DapperDutchDude/rarefriends-vibeathon/blob/main/submissions/suika-merge/game/game.json)

## Run it

Use Node.js 22+ on Linux or Ubuntu/WSL2, plus a browser wallet holding a hardwired Rare Friends Generations NFT (generation ≥ 1) on Robinhood mainnet.

```sh
git clone https://github.com/DapperDutchDude/rarefriends-vibeathon.git
cd rarefriends-vibeathon/submissions/suika-merge
npm ci
npm run dev
```

Open the printed URL, connect your wallet and select your Friend. The SDK verifies ownership before play. No RF funding or transaction signature is needed for this simulated preview. No hosted demo is provided yet.

## Play

Move the aim reticle with arrow keys or drag/tap on the jar. Press space, enter, or release your tap to drop the next fruit. Matching fruit merges on contact, climbing the tier chain and raising your multiplier. Cash out anytime to bank your current multiplier, or keep pushing your luck — if the jar overflows, that round's multiplier is lost. Settings include mute and reduced motion. Everything stays inside the SDK's 960 x 640 container.

## Rules and rewards

**All balances, purchases and rewards are simulated.** Start with 20 RF. One drop costs 1 RF. Merges resolve continuously via physics; the table below documents the net result of a single drop once its merges resolve.

| Result | Chance | Redemption value |
|---|---:|---:|
| No merge | 45% | 0 RF |
| Cherry to Grape | 25% | 0.30 RF |
| Grape to Orange | 15% | 0.70 RF |
| Orange to Apple | 9% | 1.50 RF |
| Apple to Melon | 4% | 3.50 RF |
| Melon to Watermelon | 1.5% | 9.00 RF |
| Watermelon jackpot | 0.5% | 25.00 RF |

Expected reward: **0.715 RF per drop** (a ~28.5% house edge). Shaking the jar costs 2 RF and nudges fruit toward a merge without changing underlying odds. Continuing after an overflow costs 3 RF. New drop purchases stop when balance is insufficient. Preview progress resets when the runtime session ends.

## Checks, credits and limitations

Run `npm test`, `npm run check:games`, and `npm run build`. `npm run typecheck` is a placeholder in this prototype (no TypeScript sources yet). `npm run check:browser` is not wired up yet - a real-wallet, real-browser playthrough is still outstanding.

The dropper character and jar scenery are placeholder art for this MVP and are not the final Rare Friends canonical sprites - swap in official character artwork before any production submission. No trading, wearable NFTs, creator fees, or live economy is included. Production publication needs separate Rare Friends review.
