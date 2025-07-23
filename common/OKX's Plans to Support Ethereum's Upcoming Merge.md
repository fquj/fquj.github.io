# OKX's Plans to Support Ethereum's Upcoming Merge  

Dear OKX users,  

The Ethereum (ETH) Merge is nearly finalized. This update outlines how OKX will navigate this transition while safeguarding user assets and maintaining service continuity.  

## Understanding the Ethereum Merge  

The Ethereum Merge represents a fundamental shift from a **Proof-of-Work (PoW)** consensus mechanism to a **Proof-of-Stake (PoS)** model. On September 6, 2022, the Bellatrix upgrade prepared the PoS Beacon Chain for integration with Ethereum’s existing PoW mainnet. The final phase, the Paris upgrade, will occur when the PoW chain reaches a **Terminal Total Difficulty (TTD)** of **58,750,000,000,000,000,000,000**—anticipated around 2:00 AM UTC on September 15, 2022.  

**Note:** This timing is an estimate. Monitor Ethereum’s official channels for real-time updates.  

## OKX’s Approach to Forked Tokens  

### Post-Merge Token Recognition  

Following the Merge, Ethereum’s PoS chain will retain the ETH ticker symbol. However, potential hard forks of the PoW chain may generate **forked tokens**. OKX will treat these tokens as distinct blockchain assets.  

### Snapshot Process for Forked Tokens  

If a hard fork occurs:  
- A snapshot of user ETH balances will be taken at the TTD threshold.  
- Forked tokens will be distributed at a **1:1 ratio** relative to ETH holdings at the time of the snapshot.  
- The snapshot includes ETH in trading, funding, and Grow accounts, as well as collateral for loans.  

**Loans and Repayment Requirements:**  
- Users with outstanding ETH loans must repay debts in forked tokens post-Merge.  
- Unresolved debts may result in withdrawal restrictions or USD deductions from accounts.  
- Interest rates for unpaid loans may adjust based on market conditions.  

### Calculating Total ETH Equity  

Total ETH Equity =  
(`ETH balance + unrealized PnL in trading account`) +  
(`ETH equity in funding account`) +  
(`ETH equity in Grow account`) +  
(`ETH collateral in fixed/flexible-term loans`) -  
(`ETH borrowed in fixed/flexible-term loans`) -  
(`ETH borrowed in trading activities`)  

**Exclusion Note:** ETH staked via DeFi Mining will not be included in the airdrop.  

## Impact on OKX Services  

To ensure stability, OKX will temporarily pause specific services during the Merge.  

### Service Status Updates  

| Service                | Status During Merge | Details                                                                 |
|------------------------|---------------------|-------------------------------------------------------------------------|
| **Deposits/Withdrawals** | Paused              | ETH and ERC-20 transactions will resume after network stabilization.  |
| **Transfers**           | Paused for 10 mins  | Snapshot taken at TTD; transfers resume immediately afterward.        |
| **Spot Trading**        | Operational           | ETH and ERC-20 trading pairs remain unaffected.                       |
| **Fiat Services**       | Operational           | ETH-to-fiat conversions continue.                                     |
| **Convert**             | Operational           | ETH crypto-to-crypto conversions continue.                            |
| **Earn Program**        | Partially Affected    | Interest accrual continues; deposits during the pause show "processing" until services resume. |
| **ETH 2.0 Staking**     | Paused               | Staking paused from 6:00 AM UTC, September 14, to 6:00 AM UTC, September 16. |
| **Margin Trading**      | Partially Paused      | Borrowing suspended from 7:00 AM UTC, September 14, to 4:00 PM UTC, September 15. |
| **Futures & Swaps**     | Operational           | Contracts will track PoS chain prices post-Merge.                     |
| **Options Trading**     | Operational           | Post-Merge contracts will reflect PoS ETH prices.                     |

### FAQs: Service Impact  

**Q: Will my ETH 2.0 staking rewards be affected?**  
A: BETH profit distributions will continue uninterrupted during the pause.  

**Q: Can I deposit ERC-20 tokens during the Merge?**  
A: Deposits will show as "processing" until services resume. Interest in the Earn program will begin once processing completes.  

## Risk Control Adjustments  

To mitigate volatility, OKX will adjust risk parameters for ETH trading.  

### Price Limits and Funding Rates  

| Phase                  | Upper Limit | Lower Limit |  
|------------------------|-------------|-------------|  
| First 10 minutes post-contract | Index \*(1+6%) | Index \*(1-15%) |  
| After 10 minutes       | Adjusted based on market premium | Adjusted based on market premium |  

**Funding Rate Adjustments:**  
- Effective September 14, 2022, the funding rate range for ETH perpetual swaps expands from ±0.75% to ±3%.  

### Portfolio Margin Mode Adjustments  

| Parameter              | Pre-Merge | Post-Merge |  
|------------------------|-----------|------------|  
| **Spot Shock (MR1)**   | ±15%      | ±20%       |  
| **Basis Risk (MR4)**   | 1.5%      | 5%         |  

**Actionable Advice:** Adjust margin positions to account for increased liquidation risks.  

### FAQs: Risk Management  

**Q: Why are price limits expanding?**  
A: Expanded limits accommodate potential volatility during the Merge, ensuring market stability.  

**Q: How do portfolio margin changes affect my trades?**  
A: Higher MR1 and MR4 thresholds may increase margin requirements for ETH-based risk units.  

## Grow Service Updates  

### Savings, Staking, and DeFi  

- **Savings & Staking:** Unaffected. Staked ETH is included in snapshots unless deposited via DeFi.  
- **Dual Investment & Smart Gain:**  
  - ETH subscriptions confirmed before 7:00 AM UTC, September 13, qualify for airdrops.  
  - Orders settled post-Merge receive forked tokens; pre-Merge settlements do not.  

### DeFi Protocol Suspensions  

- ETH deposits/withdrawals via DeFi will pause from 6:00 AM UTC, September 14, to 6:00 AM UTC, September 16.  
- **Risk Advisory:** Staked ETH in DeFi may not qualify for airdrops if forked chains lack support for protocols like Sushiswap.  

### FAQs: DeFi and Airdrops  

**Q: Should I unstake ETH from DeFi before the Merge?**  
A: Yes, to ensure eligibility for forked token airdrops.  

**Q: Do Smart Gain subscriptions qualify for airdrops?**  
A: Only subscriptions confirmed before September 13, 2022, and unsettled pre-Merge qualify.  

## Final Preparations and Recommendations  

- **Reduce Leveraged Positions:** Close or reduce ETH options/futures positions before September 13.  
- **Repay ETH Loans:** Avoid restrictions by settling debts pre-Merge.  
- **Monitor Announcements:** OKX will provide updates on forked token listings and service resumptions.  

👉 [Stay ahead of crypto updates with OKX](https://bit.ly/okx-bonus)  

For further details on risk control parameters, visit OKX’s **Mark Price** and **Portfolio Margin Mode** support pages.  

👉 [Explore advanced trading tools on OKX](https://bit.ly/okx-bonus)  

This transition marks a pivotal moment for Ethereum and the broader blockchain ecosystem. OKX remains committed to ensuring a seamless experience for all users.  

**Last Updated:** September 13, 2022 (UTC)