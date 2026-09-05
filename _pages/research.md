---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 1
---

<style>
  .research-item {
    display: flex;
    gap: 1.5rem;
    margin-bottom: 2.5rem;
    align-items: flex-start;
    flex-wrap: wrap;
  }
  .research-text { flex: 1 1 340px; min-width: 280px; }
  .research-fig { flex: 0 0 352px; max-width: 352px; }
  .research-fig img,
  .research-fig .fig-placeholder {
    width: 100%;
    border: 1px solid var(--global-divider-color, #e8e8e8);
    border-radius: 5px;
  }
  .research-fig .fig-placeholder {
    aspect-ratio: 4 / 3;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    font-size: 0.8rem;
    color: #999;
    background: #f6f6f6;
    padding: 0.5rem;
  }
  .research-item h3 { margin-bottom: 0.25rem; font-size: 1.1rem; color: var(--global-theme-color, #1772d0); }
  .research-authors { margin-bottom: 0.35rem; }
  .research-note { font-size: 0.95rem; color: var(--global-text-color, #333); font-style: italic; margin-bottom: 0.4rem; }
  .research-award {
    font-size: 1rem;
    font-weight: 700;
    color: var(--global-theme-color, #00356b);
    margin-bottom: 0.3rem;
  }
  .research-award i { margin-right: 0.35rem; }
  .jmp-badge {
    display: inline-block;
    font-size: 0.7rem;
    font-weight: 600;
    letter-spacing: 0.03em;
    text-transform: uppercase;
    color: #fff;
    background: var(--global-theme-color, #00356b);
    padding: 0.1rem 0.5rem;
    border-radius: 3px;
    vertical-align: middle;
    margin-left: 0.4rem;
  }
  .research-links a {
    font-size: 0.85rem;
    margin-right: 0.75rem;
  }
  details.abstract {
    margin: 0.4rem 0;
    font-size: 0.9rem;
  }
  details.abstract summary {
    cursor: pointer;
    color: var(--global-theme-color, #00356b);
    font-size: 0.85rem;
    width: fit-content;
  }
  details.abstract p {
    margin-top: 0.4rem;
    color: var(--global-text-color, #333);
    line-height: 1.5;
  }
  .research-section-title {
    border-bottom: 1px solid var(--global-divider-color, #e8e8e8);
    padding-bottom: 0.3rem;
    margin-top: 2rem;
    margin-bottom: 1.5rem;
  }
</style>

<h2 class="research-section-title">Working Papers</h2>

<div class="research-item">
  <div class="research-text">
    <h3>The Shadow Cost of the Credit Limit: Payment Choice and Household Liquidity Management<span class="jmp-badge">Job Market Paper</span></h3>
    <div class="research-authors">with Jose Murillo</div>
    <details class="abstract">
      <summary>Abstract</summary>
      <p>We study the effect of a household's credit capacity on its preference for credit or cash payments, and what that choice reveals about the shadow cost of credit. By analyzing 1.5 million consumption records linked to each household's real-time credit position, we find that the same household uses more cash as its credit utilization rises, exhibiting a convex pattern. This convexity is consistent with a precautionary mechanism: the marginal value of available credit rises as capacity shrinks, leading to a convex rise in the cost of credit for all households. Households with existing balances incur additional interest costs, prompting them to choose cash more frequently at every level of utilization. Bank-initiated increases in credit limits, which expand headroom without affecting the balance, causally reduce cash usage.  Consequently, payment choice, when observed alongside the credit position at a transaction level, serves as a direct measure of the shadow cost of drawing down borrowing capacity.</p>
    </details>
  </div>
  <div class="research-fig">
    <img src="{{ '/assets/img/papers/shadow_cost.png' | relative_url }}" alt="The Shadow Cost of the Credit Limit — key figure">
  </div>
</div>

<div class="research-item">
  <div class="research-text">
    <h3>Fintech to the (Worker) Rescue: Earned Wage Access and Employee Retention</h3>
    <div class="research-authors">with Jose Murillo and Boris Vallée</div>
    <div class="research-note">Selected for the 2023 NBER Innovative Data in Household Finance, MFA 2026, and SGF 2026</div>
    <details class="abstract">
      <summary>Abstract</summary>
      <p>We study the usage and welfare implications of earned wage access (EWA) using administrative and survey data from a Mexican FinTech provider. Adoption is significant, and usage concentrates at the end of the pay cycle. We develop a stationary buffer-stock framework, calibrated to the data, in which EWA provides liquidity insurance and consumption-timing alignment. Access is worth about 2.5\% of a paycheck per year for the average user, and an order of magnitude more for impatient, low-liquidity workers. Automatic repayment makes these gains more robust to present bias than with revolving credit. EWA usage is associated with higher employee retention, as the framework implies.</p>
    </details>
    <div class="research-links">
      <a href="https://ssrn.com/abstract=4067701" target="_blank" rel="noopener noreferrer"><i class="fa-solid fa-file-lines"></i> SSRN</a>
    </div>
  </div>
  <div class="research-fig">
    <img src="{{ '/assets/img/papers/ewa.png' | relative_url }}" alt="Earned Wage Access — key figure">
  </div>
</div>

<div class="research-item">
  <div class="research-text">
    <h3>Riding the Waves: Geographic Diversification and Bank Responses to Local Funding Shocks</h3>
    <div class="research-authors">with Wei Li and Mingmei Liu</div>
    <div class="research-award"><i class="fa-solid fa-trophy"></i>Best Paper Award, The 8th Asia Conference on Business and Economic Studies</div>
    <div class="research-note">Selected for the 2025 EWMES and 2025 Sydney Banking and Financial Stability Conference</div>
    <details class="abstract">
      <summary>Abstract</summary>
      <p>How resilient are banks to local funding shocks? We exploit a segment of Chinese wealth management products (WMPs) funded locally but backed by national assets, allowing us to isolate banks' strategic responses to local funding pressures. Using city-level inflation to characterize investor demand shifts, we find that banks pass through approximately 60% of these shocks to WMP yields. Large, geographically diversified banks respond more actively, by raising yields and contracting issuance in shock-hit markets more sharply than smaller banks. They then hedge by expanding the issuance of lower-yield WMPs in unaffected regions. Our findings reveal that for large banks, geographic diversification is not a tool for passive insulation but a mechanism enabling active, high-frequency liability management through their internal capital markets.</p>
    </details>
  </div>
  <div class="research-fig">
    <img src="{{ '/assets/img/papers/wmp.png' | relative_url }}" alt="Riding the Waves — key figure">
  </div>
</div>

<h2 class="research-section-title">Work in Progress</h2>

<div class="research-item">
  <div class="research-text">
    <h3>The Economics of Rent-to-Own Housing</h3>
    <div class="research-authors">solo-authored</div>
  </div>
</div>

<div class="research-item">
  <div class="research-text">
    <h3>Mortgage Securitization and Housing Affordability</h3>
    <div class="research-authors">with Daojing Zhai</div>
  </div>
</div>

<h2 class="research-section-title">Other Writing</h2>

<div class="research-item">
  <div class="research-text">
    <h3>A Case in Point: Shared Home Equity</h3>
    <div class="research-authors">with Boris Vallée, Daniel Green, and Sid Beaumaster</div>
    <div class="research-note">Harvard Business School Case 221-026</div>
    <div class="research-links">
      <a href="https://hbsp.harvard.edu/product/221026-PDF-ENG" target="_blank" rel="noopener noreferrer"><i class="fa-solid fa-up-right-from-square"></i> HBS Publishing</a>
    </div>
  </div>
</div>

<div class="research-item">
  <div class="research-text">
    <h3>Seso Global: Building a Blockchain-enabled Property Marketplace in Nigeria</h3>
    <div class="research-authors">with Boris Vallée</div>
    <div class="research-note">Harvard Business School Case 220-055</div>
    <div class="research-links">
      <a href="https://hbsp.harvard.edu/product/220055-PDF-ENG" target="_blank" rel="noopener noreferrer"><i class="fa-solid fa-up-right-from-square"></i> HBS Publishing</a>
    </div>
  </div>
</div>
