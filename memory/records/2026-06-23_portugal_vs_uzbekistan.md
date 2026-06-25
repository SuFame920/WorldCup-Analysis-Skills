# Portugal vs Uzbekistan — WC2026 Group K MD2

- **date:** 2026-06-23 (Houston, NRG Stadium; 北京时间 06-24 01:00)
- **status:** settled
- **comp/stage:** WC2026 Group K, Matchday 2
- **home (listed first):** Portugal · **away:** Uzbekistan

## Pre-match context (retrieved)
- Standings after MD1: Colombia 3, DR Congo 1, **Portugal 1** (1-1 vs DR Congo, Ronaldo 0 shots on target, blunt vs low block), **Uzbekistan 0** (1-3 vs Colombia, competitive spells).
- **Stakes:** Portugal must win to control top-2. Uzbekistan motivated to lose narrowly (keep goals conceded down for 3rd-place tiebreak; still alive for MD3 vs DR Congo).
- Form: Portugal won 4 of last 5 (2-1 vs Nigeria Jun 10). Uzbekistan lost to NED (Jun 8) and CAN (Jun 2).
- Lineups: Portugal full-strength elite midfield (Vitinha, J.Neves, B.Fernandes, B.Silva) + Ronaldo starts. Uzbekistan deep 4-4-2/5-4-1, Khusanov (Man City CB), Fayzullaev + Shomurodov on counter.
- Market: Portugal -600 (~80%), Draw +600, Uzbek +1600. **O/U 2.5** (Over -180 / Under +146). **体彩 葡萄牙 让1球 @1.75**. Spread Portugal -1.5 @ ~-150.
- Archetype: **elite favorite strangling a passive deep-block opponent that wants to minimize goals conceded** (same type as Arg 2-0 Austria, batch 2026-06-22). Channel H corrections applied: #1′ (totals-by-scenario → low side), #2 (don't undercap favorite margin → kept 3-0 weight), #5 (push live on integer -1), #7 (HT not auto-draw — but Portugal early-scoring shown ABSENT vs Congo, so #7 hook weak → still leaned 平胜), #8 (anti-overcorrection → did NOT slam under, kept 3球 close behind 2球).

## Prediction (posterior)
- **1X2:** Portugal win — 73/100 (matrix ~ POR 76% / draw 17% / UZB 7%; draw risk upgraded by Congo precedent)
- **让球 (体彩 葡萄牙 -1):** 让1球后葡萄牙胜 / 净胜2+ — 50/100 (push net=1 ~27% elevated by Uzbek deep block; cover ~50% single largest)
- **比分:** 2-0 (30) / 3-0 (20) / 2-1 (18) — all Portugal wins
- **大小球 (2.5):** 2 球 (50) / 3 球 (40) — leaned under vs market's Over, via strangle + keep-score-down mechanism
- **半全场:** 平胜 (HT level, FT Portugal win) — 39/100
- **爆冷概率:** ~20% — triggers: (1) Uzbek bus frustrates Portugal's misfiring attack into a draw (Congo blueprint replay), (2) Ronaldo/finishing drought + Uzbek counter/set-piece steal.

## Actual (settled 2026-06-24)
- **终场:葡萄牙 5-0 乌兹别克斯坦 | HT:3-0**
- 进球:6' C罗、17' 努诺·门德斯(任意球)、28' C罗、60' 内马托夫乌龙、87' 莱昂(替补)。C罗梅开二度,成史上首位 6 届世界杯破门球员。
- 数据:葡 17 射 xG 2.43;乌兹 7 射 xG 0.25。葡萄牙首发尽出(C罗首发),全场碾压;乌兹低位但被打崩,未能反击偷袭。阵容与赛前预计一致。

## Reflection (settled)
- **逐市场:**
  - 胜平负(葡萄牙胜):✅。
  - 让球(葡 -1,净胜2+):✅ 净胜 5,过盘(赛前担心的"净胜1走盘"未现 → 此处偏谨慎)。
  - 比分(2-0/3-0/2-1):❌ 实 5-0,三桶全封顶过低。
  - 大小球(2.5,押 2球/3球 偏小):❌ 实 5 球(Over),押小错向。
  - 半全场(平胜,HT 平):❌ 实 HT 3-0(胜胜)——默认"半场平"被 6' 进球打脸,#7 未贯彻。
  - → **5 项命中 2(1X2、让球);比分/大小/半全 三项 miss,全是"幅度/早段"低估。**
- **打分:** 1X2 Brier ≈ (1-.76)²+.17²+.07² = **.091**(log-loss −ln.76 ≈ .27);比分/大小球错向。
- **DIAGNOSIS:**
  - 大小+比分 miss ≈ **variance(上盘溢出)+ under-cap**:葡 xG 2.43 ≈ "2-3球",过程质量≈我所判,**5 球是高效终结+1乌龙+87'替补补刀的溢出**。但 #2 对**精英全主力+顶级终结者+自身动机(罗冲纪录/must-win)**一档**仍封太低**——这不是"绞杀低分",该给 4-0/5-0 更多尾部。
  - **archetype 误套**:按 Arg-Aut"绞杀被动弱旅→低分",但乌兹质量低于奥地利、葡火力/动机更高 → 同型不同档。
  - 半全场 miss = #7 未贯彻(因"罗 vs 刚果哑火"默认半场平,实际 6' 即破门)。
- **一句教训:** 精英全主力+顶级终结者+追分动机的强队对真弱旅,**比分/totals 上限要给够(4-0/5-0 尾部)、半场别默认平**;别因"绞杀 archetype"或"上一场哑火"压低幅度。
