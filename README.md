# PUMPX // Chamber of Fate (Russian Roulette)

**Live Website:** [pumpx.ratchetx.xyz](https://pumpx.ratchetx.xyz)  
**Pump.fun Pair:** [$PUMPX / $PUMP](https://pump.fun/coin/3YhNeHVNPtzm5cyFVxmzddWGJJke4n6D79KWYXPZ9xoF)  
**X (Twitter) Announcement:** [https://x.com/SonyxEth/status/2099632476553380314](https://x.com/SonyxEth/status/2099632476553380314?s=20)  
**Telegram:** [t.me/ratchetx](https://t.me/ratchetx)  

---

## On-Chain Addresses (Solana Mainnet)

- **Token Mint (CA):** `3YhNeHVNPtzm5cyFVxmzddWGJJke4n6D79KWYXPZ9xoF`
- **Quote Mint:** `$PUMP` (`pumpCmXqMfrsAkQ5r49WcJnRayYRqmXz6ae8H7H9Dfn`)
- **Program ID:** `GUkWcmnUzMPhRBtN1uNbgBSoxuW9T3SL2MT7mRcQbgHH` (Upgrade Authority: Revoked / None)
- **Chamber PDA:** `BkV8p5YMkNaJcHF88QygX4pXhxDrkiqG2uDctNToNKVt`
- **Architect Wallet:** `HXFDaHyZ3i477z1BakiTWZg9UQN8rcreruuv9ifC1HvM`

---

## Game Mechanics & Double Flywheel

1. **Double Flywheel Split:**
   - **33.67% Architect:** Sent directly on-chain to Semir Poturak.
   - **66.33% Jackpot Pot:** Continuously feeds the Chamber PDA pot.
   - Applies to both Pump.fun curve trading fee-sharing and in-game trigger pulls.
2. **Revolver Rules:**
   - 6 chambers, 1 bullet.
   - 5-in-6 chance to survive (83.33%): challenger becomes the standing survivor, initiating a 5-minute countdown clock.
   - 1-in-6 chance of BANG (16.67%): the gun fires, and the previous standing survivor instantly claims the entire pot!
   - If uncontested for 5 minutes, anyone can crank `settle` to award the survivor 90% of the pot with a 1% cranker tip.
3. **100% On-Chain & Zero Admin:**
   - Ultra-lean Pinocchio `no_std` contract compiled to 23 KB.
   - Authority revoked `--final` on mainnet.
