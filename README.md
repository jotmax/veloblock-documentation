# veloblock-documentation
This is the documentation for Veloblock
Veloblock is a decentralized finance (DeFi) protocol built on the Soroban smart contract platform (by Stellar). It focuses on providing efficient cross-border payments, flash loans, and other DeFi services for businesses and individuals, particularly in emerging markets. By locking collateral, users can access short-term liquidity to settle real-world transactions quickly and cost-effectively.

Key Features
Cross-Border Payments

Instant settlement across multiple currencies, leveraging Stellar’s infrastructure for fast and low-fee transactions.
Flash Loans

On-demand borrowing of liquidity without upfront capital provided the debt is repaid within the same transaction or by the specified deadline.
Collateralized Loan Positions (CLPs)

Users lock acceptable assets (e.g., XLM, USDC) to secure short-term loans, with flexible repayment schedules and transparent interest rates.
Rebalancing Mechanism

Automated liquidity rebalancing between currency pools to maintain stable pegs and ensure adequate liquidity is available for borrowers.
Oracles & Price Feeds

Integration with decentralized oracles for accurate, real-time asset pricing and fiat exchange rates, minimizing risks of market manipulation.
Facilitator & Fiat Redemption

Trusted partners enable direct exchange between Veloblock stablecoins and real-world fiat currencies, creating a smooth on/off-ramp experience.

veloblock/
├─ docs/
│  ├─ index.html
│  ├─ motivation-vision.html
│  ├─ system-components-overview.html
│  ├─ workflow.html
│  ├─ ...
│  └─ pricings-cross-pool-loans.html
├─ contracts/
│  ├─ CollateralLockingContract.soroban
│  ├─ FlashLoanContract.soroban
│  └─ ...
├─ scripts/
│  └─ deployment_scripts.sh
├─ README.md
└─ LICENSE
