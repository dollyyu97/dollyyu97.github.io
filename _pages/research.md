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
    <h3>The Shadow Cost of Credit: Payment Choice and Credit Capacity <span class="jmp-badge">Job Market Paper</span></h3>
    <div class="research-authors">with Jose Murillo</div>
    <details class="abstract">
      <summary>Abstract</summary>
      <p>Linking 1.5 million delivery orders to households' daily credit position, we find that a household's cash use rises in a convex pattern with its credit utilization. This pattern reflects a motive to preserve available credit for future expenditure shocks that may go on credit. As utilization rises, the remaining credit is more likely to fall short of such a shock; therefore, each dollar of anticipated consumption paid on credit costs more, and households substitute cash for credit. Using a regression discontinuity design, we show that bank-initiated limit increases reduce cash use, most among households near their limit. We estimate that for a household that pays no interest, a dollar on credit carries a shadow cost of 5 cents at 20 percent utilization and 24 cents at 80 percent, close to the 25 cents of lifetime interest on a dollar of revolving debt.</p>
    </details>
  </div>
  <div class="research-fig">
    <img src="{{ '/assets/img/papers/shadow_cost.png' | relative_url }}" alt="The Shadow Cost of Credit — key figure">
  </div>
</div>

<div class="research-item">
  <div class="research-text">
    <h3>Fintech to the (Worker) Rescue? Earned Wage Access, Worker Welfare and Employee Retention</h3>
    <div class="research-authors">with Jose Murillo and Boris Vallée</div>
    <div class="research-note">Selected for the 2023 NBER Innovative Data in Household Finance, MFA 2026, and SGF 2026</div>
    <details class="abstract">
      <summary>Abstract</summary>
      <p>We study the usage and welfare implications of earned wage access (EWA) using administrative and survey data from a Mexican FinTech provider. Adoption is significant, and usage concentrates at the end of the pay cycle. We develop a stationary buffer-stock framework, calibrated to the data, in which EWA provides liquidity insurance and consumption-timing alignment. Access is worth about 2.5% of a paycheck per year for the average user, and an order of magnitude more for impatient, low-liquidity workers. Automatic repayment makes these gains more robust to present bias than with revolving credit. EWA usage is associated with higher employee retention, as the framework implies.</p>
    </details>
    <div class="research-links">
      <a href="{{ '/assets/pdf/ewa_draft.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer"><i class="fa-solid fa-file-pdf"></i> PDF</a>
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
    <div class="research-links">
      <a href="{{ '/assets/pdf/WMP_WEI_MM_Dolly.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer"><i class="fa-solid fa-file-pdf"></i> PDF</a>
    </div>
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
