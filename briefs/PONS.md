DRY RUN – WOULD BE DROPPED: 24h vol/liq 0.12x < 2x; top-10 holders 55.70% raw (35.56% of circulating excl. burn) ≥ 30%

PONS / Robinhood Chain / 0x39dBED3a2bd333467115dE45665cC57F813C4571

Why it made the list: Owner-requested dry run. PONS is the platform token of the Pons launchpad on Robinhood Chain; the narrative is that launchpad fees buy back and burn PONS. It launched on Jul 13, 2026, right after the competing launchpad Noxa had problems.

Liquidity $2,252,757.35 (main pair Uniswap v3 PONS/WETH 0x10CC…26bA; $9,420,446.86 across all 30 pairs) | Pair age ~2,533h / ~105.5 days (created Jul 13, 2026 4:42:21 PM ET) | Vol/Liq 0.124x main pair ($279,952.90 / $2,252,757.35); 1.14x all pairs ($10,768,303.63 / $9,420,446.86); largest other pair Ramses v3 PONS/USDG 0xf2A0…B269 2.70x ($6,009,088 / $2,229,114) | Top-10 55.70% raw (incl. 0x…dEaD burn 32.79%); 23.90% of total supply / 35.56% of circulating (672.09M) excl. burn; ≈20.27% of total / ≈30.16% of circulating excl. burn, Gate.io and v4 PoolManager | Mint: no mint function (fixed 1,000,000,000 supply, _mint only in constructor, no owner; verified source) / LP: launch position locked at bytecode level (Uniswap v3 position NFT #109216 sent to locker 0x31ca…54B5 in the creation tx, block 8963150, with no transfer since; the locker's bytecode has no NFT-transfer or decreaseLiquidity call, only collect-fees, but its source is NOT verified); the other 29 pairs are UNKNOWN

Origin on X: @MEADGod (73,763 followers; Pons launchpad dev), Jul 13, 2026 4:41:08 PM ET, "Since Noxa fumbled hard on Robinhood: here you go.. pons launchpad." The launchpad announcement came 73s before the PONS pair was created and has no ticker or CA (https://x.com/MEADGod/status/2076768915145822485). First 3 distinct accounts posting the CA: @btc_789 (40,638 followers), 4:53:35 PM ET, a bare CA reply under @MEADGod's post (https://x.com/btc_789/status/2076772047062192545); @OMGmeii2xxzz (3,682), 5:19:47 PM ET, "bridged off of noxa and made way better by a better dev" + CA (https://x.com/OMGmeii2xxzz/status/2076778643171217755); @dex_kolwatcher (8,793; automated bot), 5:29:35 PM ET, "Detect PAID DEXScreener: $PONS … MC: $34,059" (https://x.com/dex_kolwatcher/status/2076781107014738067). Next was @neodot, 5:29:36 PM ET (https://x.com/neodot/status/2076781112848720066). @MEADGod first named the CA as "Official $PONS CA" at 5:48:20 PM ET, writing that "The deployer of $PONS transferred ownership and fees to my wallet" (https://x.com/MEADGod/status/2076785825262551342). Independent sources: ~32 distinct accounts with original text from launch to Jul 13, 11:59 PM ET. Collapsed into existing sources: ≥10 pure retweets (@erbettina_, @ADM4211 x3, @Dodseven77, @comfyrelax, @UTDsDad x2, @exe_plata93 x2, @mikecarter558, @valencrypto1, @bjornXBT, @BaseKael and others); repeat near-identical posts by @stadz_, @0xKanjuro0, @goalexPenn, @neodot and @Lytyrko_; and the identical "@0xDeployer $PONS <CA>" replies from @T0mmyXBT and @pn95689050, counted as 1. Paid-promotion history: @MEADGod has no disclosed paid promotion (#ad/sponsored/paid/promo). Hits were "DM for Sora codes" (Oct 2025), "this post is not sponsored by Kalshi" (Dec 2025), and a Sep 26, 2026 reply, "not the first time I got rewards through paid". @ponsdotfamily (verified, 93,812 followers) also has no disclosed paid promotion; its "paid" hits are creator-fee payout posts and a Sep 3, 2026 "partnership with @Uniswap" post. Paid status is UNKNOWN beyond disclosures.

Unknowns:
- Source code of the LP locker 0x31ca5E101941A93A7DD6d0497928700625CF54B5 (unverified; the lock was judged from bytecode selectors only)
- LP lock/burn status of the 29 non-launch pairs (≈$7.17M of liquidity outside the main pair)
- Identity and control of 0xB995B91882F5990e5aB3Cc4700b66b20A66C4C79 (7.54%) and holders 0xa647…98BA, 0x295C…AA36, 0xc0E1…62ae, 0xED9A…8771, 0x0a6E…119E, 0x88D2…51d3, 0x2dBA…5b1a, and what the ERC1967 proxy 0x73D8…46Db (1.25%) is
- Who the deployer 0xB9F5f4Ea1AF1F5d3678470eb98e8FBdcadEb24b0 is, and whether 0xf89F3858Bc7bac05a83Ec284E3E9AcDb58BF892A (launch-tx buy of 68,057,245 PONS = 6.81%) is @MEADGod's wallet (he posted at 5:14 PM ET that he "Burned the PONS that was sent to me (Total was like 69…)", which is not linked on-chain here)
- The launch factory 0x0c37a24F5D23A486FA692d1500881d698B1F77a4 (unverified; the Blockscout fetch timed out)
- Who paid for the DEX Screener profile flagged at 5:29 PM ET Jul 13
- Why Blockscout's 24h volume ($20.74M) differs from DEX Screener's all-pairs 24h volume ($10,768,303.63)
- The ticker-only X search (PONS + robinhood/ponsdotfamily) was paged back only to 8:59 PM ET Jul 13. The CA search was fully paged (no posts before 4:53 PM ET). Pre-launch posts were searched from Jul 12 for the ticker only.
- A post quoted by @MEADGod's origin post (2076573155183796384) was not readable via X ("Not Found")
- Whether any early callers were paid

Red flags:
- Top-10 holders 55.70% raw, 35.56% of circulating excl. burn; a single EOA (0xB995…4C79) holds 7.54%
- Fails the vol/liq cutoff: 0.124x main pair, 1.14x all pairs
- The token was deployed by an unidentified address (0xB9F5…24b0), not shown to be the launchpad dev. "Official" status came 66 min after launch, when the dev said the deployer handed him ownership and fees.
- The launch tx carried an atomic buy of 6.81% of supply for 0.1 WETH to 0xf89F…892A
- A paid DEX Screener profile was detected 47 min after launch, at a ~$34k market cap, by an unknown payer
- The official X account @ponsdotfamily was created Jul 13, 2026 6:27:49 PM ET, about 1h45m after the pair; the token's on-chain twitter field is empty, and DEX Screener lists @ponsdotfamily
- Website domain mismatch: pons.family (token metadata/launchpad) vs ponsfamily.com (DEX Screener link)
- Launch-day security flags: a user asked why FOMO showed PONS as a scam token (https://x.com/bwollrich/status/2076839492355584320); the dev acknowledged platforms flagging Pons coins and said he contacted Blockaid (https://x.com/MEADGod/status/2076819124836049273)
- The LP locker is unverified. Its owner can raise the protocol fee share from 10 up to 50 (constructor arg 10, cap 50).
- Liquidity is fragmented across 30 pairs; only the launch position was checked
- Volume sources disagree: Blockscout $20.74M vs DEX Screener $10.77M (24h)
- Early callers framed it as "the PumpFun of Robinhood"; replies joked "Pons... Ponsi... Ponzi" (https://x.com/cryptochad215/status/2076877213316645267)

Scan complete. Awaiting approval before Analyst starts.

DRY RUN
ANALYST – Oct 27, 2026 5:52 AM ET
Order size tested: $50
Price impact: entry ≈0.004% / exit ≈0.004% (full-range approximation against main pair 0x10CC…26bA reserves of 5,076,570 PONS + 435.5 WETH from DEX Screener; exact concentrated-liquidity impact UNKNOWN)   Pool fee: 1% (fee tier 10000, from the PoolCreated event in launch tx 0x1f54f25f…af8)
Top-10 (ex-LP): 23.90% of total supply (excl. 0x…dEaD burn, v4 PoolManager and the Ramses pool; same as Scout)  Largest wallet: 0xB995…4C79 7.54%, 30-day behavior: 2,321 PONS transfers since block 73841430 (Sep 27–Oct 27 5:38 AM ET); 82,413,678 in / 33,164,477 out (net +49.25M); 364 distinct senders and 329 distinct recipients; largest counterparty is #4 holder 0xa647…98BA (52.74M in / 11.35M out). The pattern looks like exchange deposits and withdrawals, but the label is UNKNOWN
Insider flags: origin post 4:41:08 PM ET Jul 13 came 73 s before the token existed (created 4:42:21 PM, block 8963150), so no buyer can share that minute. During the minute of the "Official $PONS CA" post (5:48:20 PM ET), 14 wallets bought 97.58M PONS (9.76% of supply) from the main pair between 5:48:28 and 5:48:59 PM. They include 0x78e8…cad6 16.71M (8 s after the post), 0xd269…a1c0 15.31M and 0xc4da…f04f 14.07M, plus a 4-wallet cluster (0xbe05…a8f2, 0x6bf3…afde, 0x6a18…bdbe, 0x6c11…ddbd) that bought ≈9.4M each in matching sizes in the same seconds (5:48:37, :39, :58). None of the 14 is in today's top 50. Also an early buyer: 0x0aa9…8c1c took 3.16M 29 s after the pair was created (4:42:50 PM, tx 0x9f8cda15…)
Priority checks: (1) CONFIRMED – the token has no owner (immutable deployer, no Ownable), so there is no token ownership transfer; the on-chain handoff was deployer 0xB9F5…24b0 calling setFeeRedirect(PONS → 0xda4b…2043) on locker 0x31ca…54B5 at 5:41:36 PM ET Jul 13 (block 8998627, tx 0xa76d1339…906c), 59 min after launch and 7 min before the dev's "deployer transferred ownership and fees to my wallet" post; 0xda4b created and owned the locker and factory, which moved to Safe multisig 0x263e…19dd on Aug 27 2:31:19 AM ET (block 47230445, tx 0xe81594d9…228c); that 0xda4b is @MEADGod is UNKNOWN on-chain (2) CONFIRMED – the 68,057,245 PONS launch buy (to 0xf89F…892A, 4:42:21 PM ET, tx 0x1f54f25f…af8) was burned, none sold: 30,667,404.69 to 0x…dEaD at 4:51:45 PM (tx 0x50078910…a410) and 39,000,000 at 5:13:45 PM (tx 0xcc7365e8…9d9d); 0xf89F has burned 71,648,376.62 PONS in total and sent 126,835 to 0x3c14…1560; it now holds ≈6.4 PONS (3) UNKNOWN (current status) / basis partly CONFIRMED – the flag came from FOMO (user question 9:21 PM ET Jul 13, https://x.com/bwollrich/status/2076839492355584320); the dev's stated reason was unverified contracts ("Probably the reason why platforms flag @ponsdotfamily coins.. but I just verified the contracts", 8:00 PM ET Jul 13, https://x.com/MEADGod/status/2076819124836049273); separately the website was flagged by Google, Cloudflare and VirusTotal, and the dev said the Google flag was removed on Jul 23 1:26 AM ET (https://x.com/MEADGod/status/2080162630920962113); the token source is now verified, but locker 0x31ca, factory 0x0c37, the burn implementation and fee router 0x31ea are still unverified, so the stated basis still partly applies; FOMO/Blockaid's current rating cannot be read with our access (4) CONFIRMED no withdrawal path for the launch NFT #109216 – the locker bytecode has no decreaseLiquidity, NFT transfer, approve, delegatecall or selfdestruct, only collect plus ERC20 transfer of fees; the source is unverified and the locker owner (Safe 0x263e) can change fee share and fee collectors; all other liquidity is removable (see LP per pair) (5) CONFIRMED controller / pause FAILED-to-exclude – burns come from 0x5795…c324 (999 of the last 1,000 burns; 413,956 PONS Oct 24 7:40 PM–Oct 27 5:42 AM ET; 63,618 PONS across 195 burns from 7:31 PM Oct 26 to 5:49 AM Oct 27, funded by 6.77 WETH swapped into the main pair and fee tokens from 0x31ea…2cdb, both created by 0xda4b); 0x5795 is a UUPS ERC1967 proxy whose owner is 0xda4b (single address, never moved to the Safe), keeper 0x0b40…3f20; it was upgraded 7 times Sep 2–Oct 16 (latest Oct 16 12:14 AM ET to unverified implementation 0xa0f76089…1c76, tx 0x9dfe1e20…7fb5); the bytecode has no pause()/paused() selectors and no Paused or RoleGranted events exist, but the owner can upgrade or stop it at will, so it is pausable in effect by one address
Contract: mint CONFIRMED none (_mint only in constructor, verified source) / freeze CONFIRMED none / LP per pair (11 pairs >$50k): launch NFT #109216 in main pair 0x10CC CONFIRMED locked, but its share of that pair is UNKNOWN; LP removals observed (so removable) on 0x10CC (860 nonzero Burns in first 1,000 logs, first Jul 13 6:01 PM ET), Ramses 0xf2A0 (352), 0xEd50 (632), aero 0xD757 (318), Ramses 0x51B6 (249), 0x25C9 (283), 0x2F39 (305), 0x7A19 (711), and v4 pools 0x4be9… (319 negative ModifyLiquidity), 0x4864… (205), 0xb590… (188); FAILED for "locked" on all except the launch NFT / proxy CONFIRMED none on token (IsProxy false; the burn contract is a proxy) / tax CONFIRMED none / blacklist CONFIRMED none (only launch-window maxWallet/maxTx and a launch-block buy block, factory-gated)
Narrative: PONS is the token of the Pons launchpad (pons.family) on Robinhood Chain, where platform fees are used to buy back and burn PONS.
Narrative vs. data: SUPPORTED – a live buyback-and-burn is on-chain (0x5795 swaps WETH and fee tokens into the main pair and burns to 0x…dEaD every few minutes; 413,956 PONS in ~58 h); the original locker logged 451+ launch locks in its first 1,000 events. Caveats: the launch-path contracts 0x31ca and 0x0c37 had zero logs in the last 24 h (launches now go through other contracts: 0x31ea, created by 0xda4b, is unverified), so how many burns come from launchpad fees today is not traced end to end; the Jul 13 claim of "117.5M burned from platform fees" (7:50 PM ET) included the 69.67M from the launch-buy wallet
Origin account track record: @MEADGod (Ozzy, "Pushin' 🅿️ at @ponsdotfamily", 73,762 followers, account created May 20, 2024): 2025–Jun 2026 built CIMS / SDK at @rootsfi (Canton), and no token outcome was traceable; Mar 11, 2026 posted that launching a token is "essentially suicide" and altcoins are "uninvestable"; Jul 13, 2026 launched/claimed PONS (Official CA 5:48 PM ET), now FDV ≈$164.5M per DEX Screener and 105 days old; no earlier token he launched was found on X
Unknowns:
- Whether 0xda4b…2043 is @MEADGod – a signed message or an on-chain link posted by the dev would resolve it
- Current FOMO/Blockaid scam rating – access to the FOMO app or Blockaid API/report status
- Source of the burn implementation 0xa0f76089…1c76, fee router 0x31ea…2cdb, locker 0x31ca and factory 0x0c37 – verified source on Blockscout
- Share of main-pair liquidity held by locked NFT #109216 and exact price impact – eth_call access (positions(), slot0/tick liquidity), which this API does not support (module=proxy unsupported)
- Labels for 0xB995…4C79 and 0xa647…98BA (likely exchange wallets) – exchange attribution data
- Today's launch count on Pons (third-party post claims 1,189 on Oct 26, https://x.com/asterismaiagent/status/2114826805677109529) – address of the current launch factory to count its events
- LP-removal counts are lower bounds (getLogs capped at 1,000 rows) – paging by block range
Disqualifiers:
- Vol/Liq 0.12x on main pair (<2x threshold; from Scout)
- Top-10 35.56% of circulating ex-burn (≥30% threshold; from Scout)

Analysis complete. Awaiting approval before Risk starts.

DRY RUN – RISK – Oct 27, 2026 2:53 PM ET
Account: $1,000 (paper)
Position size: $0 (0% of account)
Dollar risk at stop: $0
Unknowns counted: 7  Disqualifiers: 2
Size reductions applied:
- Disqualifier 1: 24h vol/liq 0.12x main pair, below the 2x minimum (Scout, carried by Analyst). Size set to 0.
- Disqualifier 2: Top-10 holders 35.56% of circulating supply ex-burn, at or above the 30% limit (Scout, carried by Analyst). Size set to 0.
- The count of 7 unknowns is also above the 3-unknown limit. Size set to 0 on this rule alone.
- For reference only: 3 unknowns touch contract safety or liquidity (unverified burn implementation, fee router, locker and factory; locked share of the main pair; LP-removal counts that are only lower bounds). Those would have cut the $50 max to $6.25 before the zero rules apply.
- Analyst tested $50, which is above the $0 allowed.
Invalidation conditions (kept on file in case the disqualifiers clear on a re-scan):
1. Burn proxy 0x5795…c324 is upgraded again, or its owner 0xda4b…2043 changes, as shown by an Upgraded or OwnershipTransferred event.
2. No burns to 0x…dEaD from 0x5795 for 6 hours in a row (the current pace is every few minutes).
3. Locker 0x31ca owner (Safe 0x263e…19dd) raises the protocol fee share above 10, or changes fee collectors or the PONS fee redirect.
4. Main pair 0x10CC…26bA liquidity drops below $1.8M on DEX Screener.
5. Total liquidity across all pairs drops below $7.5M.
6. A single LP removal larger than $250k on any pair.
7. Wallet 0xB995…4C79 (7.54%) or 0xa647…98BA sends more than 1% of supply (10M PONS) to a DEX pair in 24h.
8. Any top-10 wallet, excluding the burn address and pools, sells more than 25% of its holdings in 24h.
9. FOMO, Blockaid, or another wallet scanner shows PONS as malicious, or @MEADGod or @ponsdotfamily is suspended or deleted.
Correlation check: no open positions. CASHCAT, also on Robinhood Chain, was a SIZE ZERO dry run and holds no exposure. PONS's origin is @MEADGod and CASHCAT's is @Bend756, so there's no same-origin overlap. Chain concentration: 0% on Robinhood Chain.
Verdict: SIZE ZERO

Risk complete. Awaiting approval before Execution starts.

DRY RUN – EXECUTION – Oct 27, 2026 2:55 PM ET
Pair / chain / contract: PONS/WETH Uniswap v3 0x10CC…26bA / Robinhood Chain / 0x39dBED3a2bd333467115dE45665cC57F813C4571
Size: $0  Quantity: 0 tokens
Entry: NONE – Risk verdict SIZE ZERO; no order ticket drafted
Stop: N/A  Dollar risk: $0 (verified: Risk's $0 size)
Target 1: N/A
Target 2 / trailing: N/A
Time stop: N/A
Invalidation status: not evaluated – no position to protect; Risk's 9 conditions stay on file for a re-scan
Estimated fees and gas: $0

NO ORDER. Size is $0 per Risk (2 disqualifiers, 7 unknowns). Size not changed.

REVIEWER BASELINE – Oct 27, 2026 4:41 PM ET (taken ~1h46m after the 2:55 PM no-order decision)
Reference price: $0.2551 (DEX Screener, main pair 0x10CC…26bA), FDV $171.46M, main-pair liq $2.33M, 24h vol $259.5k. Full review due after 24h (Oct 28, 2026 2:55 PM ET).

HUMAN DECISION – Oct 27, 2026 4:40 PM ET
REJECTED, dry run. Failed vol/liq and holder concentration; unverified locker, unidentified deployer, launch-day scam flag.
