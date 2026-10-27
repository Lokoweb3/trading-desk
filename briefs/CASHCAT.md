DRY RUN – WOULD BE DROPPED: 24h vol/liq 0.08x < 2x; top-10 holders 37.54% ≥ 30%

CASHCAT / Robinhood Chain / 0x020bfC650A365f8BB26819deAAbF3E21291018b4

Why it made the list: Owner-requested dry run. The token uses a "Robinhood's original name was Cash Cat" narrative, its token metadata links Vlad Tenev's tweet (x.com/vladtenev/status/1382390320663560197), and it was launched on the Noxa launchpad.

Liquidity $1,902,426.01 (main pair; $4,981,563.87 across all 30 pairs) | Pair age ~3,132h / ~130 days (created Jun 18, 2026 4:01 PM ET) | Vol/Liq 0.086x main pair ($163,152.43 / $1,902,426.01); 0.39x all pairs ($1,935,442.63 / $4,981,563.87) | Top-10 37.54% raw (≈37.0% excl. burn + LP pool; ≥34.3% excl. burn, LP and 2 Gate.io wallets) | Mint: no mint function (fixed 1,000,000,000 supply, minted only in the constructor) / LP: launch position locked (Uniswap v3 position NFT #100 held by the LaunchLocker contract, which has no withdraw path); the other 29 pairs are UNKNOWN

Origin on X: @Bend756 (808 followers), Jun 18, 2026 5:03:51 PM ET, "robinhood chain L2 / cashcat / mc 22.5k" + Noxa link carrying the CA (https://x.com/Bend756/status/2067714936474849709). Next distinct accounts: @MichealOtm, 5:08:31 PM ET, a reply question "Cashcat or Stonks?" to @FreshAlpha_ (https://x.com/MichealOtm/status/2067716109965431235); @yeon__ (20,984 followers), 5:09:42 PM ET, the first post with the CA in its text, "robinhood= cash cat" (https://x.com/yeon__/status/2067716407320776881; a near-identical repost at 5:15:26 PM ET counted as the same source). Independent sources: ~13 distinct accounts with original text between launch and Jun 19, 8:00 PM ET (2 retweets of @FreshAlpha_ collapsed into 1; @Ajon_Alpha is a buy-bot alert). Paid-promotion history of the origin account (@Bend756): no disclosed paid promotion (#ad/sponsored/paid) found. The account mostly posts NFT giveaway/collab retweets and mentions a Telegram call channel, so paid status is UNKNOWN.

Unknowns:
- Lock terms for the launch LP (LaunchLocker has no unlock function in its verified source, but the contract is only "partially verified" on Blockscout)
- LP lock/burn status of the 29 non-launch pairs (incl. ~$3.08M of liquidity not in the main pair)
- Identity and control of the top holder 0x841ed663F2636863D40be4EE76243377dff13a34 (EOA, 17.83%) and holders #2–#4, #8, #9
- Whether the deployer 0xcdfc08A1C1FBaFB355645E5ddC32122e5716cA90 still holds its launch-block buy (14,395,207.59 CASHCAT ≈1.44%)
- Whether @Bend756 or other early callers were paid
- Why Blockscout's 24h volume ($5,975,324) differs from DEX Screener's all-pairs 24h volume ($1,935,442.63)
- Pre-launch X activity before Jun 18, 3:00 PM ET was not searched
- One referenced post (2067696932621791461, @stonksrobinhood, quoted by @FreshAlpha_) was not readable via X ("not authorized")

Red flags:
- Top-10 holders 37.54% of supply; a single EOA holds 17.83%
- Fails the vol/liq cutoff: 0.086x main pair, 0.39x all pairs
- Deployer bought ~1.44% of supply in the launch block (same tx as pool creation)
- Borrowed-brand narrative: uses Robinhood's name/history and links the Robinhood CEO's tweet, with no evidence of affiliation
- Liquidity is fragmented across 30 pairs; only the launch position is verifiably locked
- Deployer earns 35% of LP fees from the locked position via LaunchLocker.collectFees (protocolFeeShare = 65)
- @FreshAlpha_ claims a "$4k" CASHCAT call, but their first public CASHCAT post found is Jun 18, 11:19 PM ET, after @Bend756's post at a 22.5k market cap; the claim is not supported by public X posts (https://x.com/FreshAlpha_/status/2067843523425054877)
- Launch-factory address 0xD9eC…FCcB holds spam "Robinhood Gift" phishing NFTs (robinhood-claim.org / .pages.dev); these are airdropped spam and not acted on
- Volume sources disagree: Blockscout $5.98M vs DEX Screener $1.94M (24h)

Scan complete. Awaiting approval before Analyst starts.

DRY RUN – ANALYST – Oct 27, 2026 5:06 AM ET
Order size tested: $50
Price impact: entry ~0.01% / exit ~0.01% (main pair Uniswap v3 CASHCAT/WETH 0xA70f…E313, 1% fee tier; RPC slot0 in-range L ≈ 9.89e22 → $50 buy moves price 0.0067%, $50 sell 0.0067%, both stay inside the current tick range [-100800,-100600] which holds ≈5.59 WETH / ≈20,111 CASHCAT ≈ $1.95k per side; DEX Screener reserves cross-check 357.85 WETH / 11.32M CASHCAT, $1.93M liq → ≤0.012%. Concentrated-liquidity caveat: depth outside the current range not mapped. Pool fee 1% per side is a cost, not price impact.) → passes the 2% test
Top-10 (ex-LP): ≈37.0% (Scout, known FAIL – not re-tested)  Largest wallet: 17.83% (0x841e…3a34), behavior UNKNOWN – DATA FAILED: Blockscout (robinhoodchain.blockscout.com returns a Cloudflare challenge/403 to this box; api.blockscout.com requires an API key)
Contract: mint CONFIRMED (no mint fn, per Scout) / freeze UNKNOWN / LP launch position CONFIRMED locked (per Scout), other 29 pairs UNKNOWN / tax UNKNOWN; proxy/upgradeable UNKNOWN; blacklist UNKNOWN – all DATA FAILED: Blockscout
Narrative: "Robinhood's original name was Cash Cat," so CASHCAT is the cat meme of Robinhood Chain, launched on Noxa and called by @Bend756 at a 22.5k mcap.
Narrative vs. data: UNCLEAR – there's no on-chain or public evidence of any Robinhood affiliation (borrowed brand). Holder control, LP status of 29 pairs and contract functions couldn't be tested. @Bend756 is a serial small-cap caller who later reused the same "original company name" lore for another token ("bifs", Circle's original name, Sep 16 2026: "same lore like cashcat only 16k mcap").
Unknowns:
- 29 non-launch pairs: LP lock/burn holder for each (≈$3.12M, ~62% of the $5.05M total DEX Screener liquidity) – DATA FAILED: Blockscout
- Top holder 0x841ed663…3a34 (17.83%): recent activity and identity – DATA FAILED: Blockscout
- Control of holders #2–#4, #8, #9 – DATA FAILED: Blockscout
- Whether deployer 0xcdfc08A1…cA90 still holds its 14.4M (≈1.44%) launch buy – DATA FAILED: Blockscout
- Wallets buying in the same minute as the origin post (Jun 18 2026 5:03 PM ET) – DATA FAILED: Blockscout; possible-insider check not done
- Freeze, proxy/upgradeable, tax, blacklist functions – DATA FAILED: Blockscout
- Liquidity depth outside the main pair's current v3 tick range
- Whether @Bend756 was paid (carried over from Scout; account advertises a Telegram call channel)
- Outcomes of most other @Bend756 calls ($yoink, $marian, $fefer, doge potato, tetherman, ozzy cat, moonkey, bifs, $spark, 0xD015…7777) were not traced
Disqualifiers: Top-10 37.54% ≥30% (Scout, known); 24h vol/liq 0.086x <2x (Scout, known). No new disqualifier confirmed; liquidity vs. $50 passes.
@Bend756 track record (X): CASHCAT itself, called Jun 18 at 22.5k, he claimed "now 8M" on Jul 2 (https://x.com/Bend756/status/2072583719567999239). $banger was "aped at 42k" Aug 7 and was "25k mcap now… still hold to zero" 1h later (https://x.com/Bend756/status/2085738335138623791); CA 0xc439…8a59 has no DEX Screener pairs today. $birdie (arc) was called at 60k on Aug 2 (https://x.com/Bend756/status/2083819286888689758) and is $5,987 mcap / $6.4k liq on DEX Screener today. Self-reported Telegram calls: $yoink 21k→331k and $marian →400k (unverified).

Analysis complete. Awaiting approval before Risk starts.

DRY RUN – ANALYST – Oct 27, 2026 5:24 AM ET
Order size tested: $50
Price impact: entry ~0.01% / exit ~0.01% (reused: main pair Uniswap v3 CASHCAT/WETH 0xA70f…E313, in-range calc 0.0067% each way, DEX Screener reserve cross-check ≤0.012%; passes 2% test)   Pool fee: 1% per side (fee tier 10000), separate from impact
Top-10 (ex-LP): 37.02% (ranks 1–6, 8, 9, 12, 13 via Blockscout getTokenHolders; excludes 0x…dead 1.226%, LP pools 0xa70f… 1.141% and 0xd42a… 1.121%; exchange wallets NOT excluded – the API returns no labels, Scout's 2 Gate.io wallets unidentified)  Largest wallet: 17.83% 0x841ed663f2636863d40be4ee76243377dff13a34, 30-day ACCUMULATING (144 transfers Sep 28–Oct 27: in 101,408,098 / out 61,205,872 / net +40,202,226 ≈ +4.02% of supply; 35,425,372 received from holder #4 0x1a18a8b9…a4e7 (2.11%) = linked wallets; 4,000,000 sent to holder #18 0x1887fa9e…3cdd); #2 5.63% 0x65b0141486541fd041ecc3e9dec797c5529b4474, 30-day ACCUMULATING (104 transfers Sep 27–Oct 26: in 21,617,625 / out 7,377,092 / net +14,240,533 ≈ +1.42%; 18,647,939 in from 0x32d4703e…5145)
Insider flags: 0x3ace8ca50c299649b888b26474cc723e90712d39 bought 10,393,143.92 (1.04%) from main pool at 5:03:00 PM ET Jun 18 (tx 0x928e0c1ec539a1217cb839e11f5cb335193848f941a1afb33f147e36aae7b8c4, 51s before the 5:03:51 PM post), now holds 5 wei (exited); 0xbe3d19e56d1dd610a4e18201366346e3db967daa bought 4,789,655.97 (0.48%) at 5:03:16 PM ET (tx 0xe86fc197894056b0801c0e654e27e75bcc004c915d555c802795b9729843a455, 35s before the post), now holds 0 (exited). Only 2 buys in that minute (blocks 90087–90105); both are possible insiders.
Contract: mint CONFIRMED absent (verified LaunchToken source; _mint only in constructor, fixed 1B) / freeze CONFIRMED none (no owner/pause) / LP per pair: [1] v3 WETH 0xA70fc67C…E313 $1.93M – launch NFT #100 CONFIRMED locked (held by LaunchLocker 0x7f03effb…cd85 since block 88836, 0 DecreaseLiquidity, verified locker has no withdraw/transfer function); other positions CONFIRMED removable (505 non-zero Burns in first 1,000 Burn logs); locked share of current liquidity UNKNOWN; [2] v3 WETH 0xd42A4910…2b09 $1.42M – CONFIRMED removable/not locked (707 non-zero Burns); [3] v4 USDG 0xa92a3df2…818b $410k – CONFIRMED removable (397 removals); [4] v4 ETH 0xf7dc0af9…50b1 $238k – DATA FAILED: Blockscout getLogs returned "Upstream service temporarily unavailable"; [5] ramses v3 USDG 0xF896fD1E…18f6 $163k – CONFIRMED removable (246 non-zero Burns); [6] v4 ETH 0x286f707c…0aa2 $150k – CONFIRMED removable (227 removals); [7] v4 USDG 0x31608601…6212 $142k – CONFIRMED removable (202 removals); [8] v3 USDG 0x4B0c312f…D0E1 $104k – CONFIRMED removable (748 non-zero Burns); [9] up v3 WETH 0x4E8649Be…917b $93k – CONFIRMED removable (332 non-zero Burns); [10] v4 ETH 0x4b4d85c5…d266 $92k – CONFIRMED single position added Oct 26 12:25 PM ET and fully removed 12:45 PM ET (net 0 in logs; conflicts with DEX Screener $92k); [11] v4 ETH 0xab201d73…72e8 $91k – CONFIRMED single position added Oct 26 9:57 AM ET and fully removed 10:05 AM ET (net 0 in logs; conflicts with DEX Screener $91k); no pair has a burned LP / proxy CONFIRMED none (IsProxy false, no upgrade logic) / tax CONFIRMED none / blacklist CONFIRMED none (only launch-window maxTx/maxWallet limits and launch-block buy block in _update)
Narrative: "Robinhood's original name was Cash Cat," so CASHCAT is the cat meme of Robinhood Chain, called by @Bend756 at 22.5k mcap on Jun 18.
Narrative vs. data: UNCLEAR – no on-chain or public evidence of any Robinhood affiliation (borrowed brand); data shows two accumulating whales (17.83% + linked #4 2.11%, 5.63%), two same-minute pre-post buyers who have exited, and removable LP on 9 of 11 pairs above $50k.
Origin account track record: CASHCAT – Jun 18 2026 at 22.5k → $95.2M FDV on DEX Screener today (he posted "now 8M" Jul 2, "250M" Aug 27); $birdie (arc, 0x8e60…8fc4) – Aug 2 at 60k → $5,987 mcap / $6.4k liq today; $banger (0xc439…8a59) – Aug 7 "aped at 42k" → he posted "25k mcap… hold to zero" 1h later, no DEX Screener pairs today, outcome UNKNOWN; 0xD015…7777 – Jul 22 → no DEX Screener pairs, UNKNOWN; $yoink – Jul 5 at 21k → self-reported 331k Jul 8, UNKNOWN (no CA); $marian – Jul 6 dip call → self-reported 400k then 1.8M Jul 10, UNKNOWN; pootye – Jul 6, UNKNOWN; acorns NFT – Jul 6, UNKNOWN; tetherman – Jul 23 at 110k, UNKNOWN; doge potato – Jul 23 at 26k, UNKNOWN; $fefer – Jul 28 "buy more at 3.7M", UNKNOWN; meow – Aug 2 x4 claim, UNKNOWN; $pons – Aug 5 dip buy, UNKNOWN; $spark – Aug 22, UNKNOWN; cat on Base/BSC – Aug 22, UNKNOWN; first cat on @ponsdotfamily – Aug 27/28 at 18k, UNKNOWN; moonkey – Aug 28, UNKNOWN; ozzy cat – Aug 30, UNKNOWN; bifs – Sep 16 at 16k ("same lore like cashcat"), UNKNOWN; $send – Sep 24 self-reported 2.4M→16M, UNKNOWN; rise punk NFT – Sep 25, UNKNOWN
Unknowns: Exchange wallets in top-10 – address labels (Blockscout v2 address endpoint/labels or exchange disclosure) would resolve; Identity/control of 0x841e…3a34, 0x1a18…a4e7, 0x65b0…4474 and their counterparties 0x040d6d…0f3f, 0xe95b02…aec9, 0x32d470…5145 – address labels or contract-code check (eth_getCode) would resolve; Pair [4] 0xf7dc…50b1 LP status – a successful Blockscout getLogs on PoolManager 0x8366…0951 would resolve; Share of main-pair liquidity held by locked NFT #100 vs. removable positions – position state reads (eth_call NPM positions / StateView) would resolve; Current LP holders for pairs [2]–[9] (logs capped at first 1,000 rows) – paged getLogs plus NFT owner reads would resolve; Why DEX Screener shows ~$91–92k on pairs [10]/[11] while logs show net-zero positions – StateView getLiquidity read would resolve; Whether same-minute buyers 0x3ace…2d39 / 0xbe3d…7daa are tied to the deployer or @Bend756 – their tokentx/txlist funding trace would resolve; Whether @Bend756 was paid – disclosure or wallet link would resolve; Outcomes of 18 untraced @Bend756 calls – their contract addresses (behind t.co links) would resolve
Disqualifiers: Top-10 37.54% raw / 37.02% ex-LP ≥30% (Scout, known); 24h vol/liq 0.086x <2x (Scout, known)

Analysis complete. Awaiting approval before Risk starts.

DRY RUN – RISK – Oct 27, 2026 5:28 AM ET
Account: $1,000 (paper)
Position size: $0 (0% of account)
Dollar risk at stop: $0
Unknowns counted: 9  Disqualifiers: 2
Size reductions applied:
- Disqualifier 1: Top-10 holders 37.54% raw / 37.02% ex-LP, at or above the 30% limit (Scout, confirmed by Analyst). Size set to 0.
- Disqualifier 2: 24h vol/liq 0.086x main pair, below the 2x minimum (Scout). Size set to 0.
- Unknown count of 9 is also above the 3-unknown limit. Size set to 0 on this rule alone.
- For reference only: the 4 unknowns touching liquidity (pair [4] LP status, locked share of main pair, current LP holders of pairs [2]–[9], pairs [10]/[11] liquidity conflict) would have cut the $50 max to $3.13 before the zero rules apply.
- Analyst tested $50, which is above the $0 allowed.
Invalidation conditions (kept on file in case the disqualifiers clear on a re-scan):
1. Main pair 0xA70f…E313 liquidity drops below $1.5M on DEX Screener.
2. Total liquidity across all pairs drops below $4.0M.
3. Wallet 0x841e…3a34 (17.83%), or its linked wallet 0x1a18…a4e7, sends more than 1% of supply (10M CASHCAT) out in 24h.
4. Any top-10 wallet sells more than 25% of its holdings in 24h.
5. A single LP removal larger than $250k on any pair.
6. @Bend756 deletes the origin post (status 2067714936474849709) or the account is suspended.
7. Robinhood or Vlad Tenev publicly disowns the token or the brand use.
Correlation check: no other open positions on record; no other @Bend756-origin or Robinhood Chain exposure to count against the 5% cap.
Verdict: SIZE ZERO

Risk complete. Awaiting approval before Execution starts.

DRY RUN – EXECUTION – Oct 27, 2026 5:30 AM ET
Pair / chain / contract: CASHCAT/WETH Uniswap v3 0xA70f…E313 / Robinhood Chain / 0x020bfC650A365f8BB26819deAAbF3E21291018b4
Size: $0  Quantity: 0 tokens
Entry: NONE – Risk verdict SIZE ZERO; no order ticket drafted
Stop: N/A  Dollar risk: $0 (verified: Risk's $0 size)
Target 1: N/A
Target 2 / trailing: N/A
Time stop: N/A
Invalidation status: not evaluated – no position to protect; conditions stay on file for a re-scan
Estimated fees and gas: $0

NO ORDER. Size is $0 per Risk (2 disqualifiers, 9 unknowns). Size not changed.

REVIEWER BASELINE – Oct 27, 2026 5:31 AM ET
Reference price at no-order decision: $0.09620 (DEX Screener, main pair 0xA70f…E313), FDV $95.02M, main-pair liq $1.93M, 24h vol $232.2k. Full review due after 24h (Oct 28, 2026 5:30 AM ET).

HUMAN DECISION – Oct 27, 2026 4:42 PM ET
REJECTED, dry run. Failed holder concentration and vol/liq; insider buys before origin post; liquidity withdrawable on 9 of 11 pairs; origin caller's prior calls collapsed.
