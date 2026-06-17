---
layout: page
permalink: /research/
title: research
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
  .research-fig { flex: 0 0 230px; max-width: 230px; }
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
  .research-item h3 { margin-bottom: 0.25rem; font-size: 1.1rem; }
  .research-authors { margin-bottom: 0.35rem; }
  .research-note { font-size: 0.85rem; color: #777; font-style: italic; margin-bottom: 0.4rem; }
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
      <p>We investigate how the shadow cost of borrowing limits drives high-frequency payment choices, exploiting transaction-level variation in real-time credit utilization, consumption baskets, and credit limit changes. We develop a theoretical framework of precautionary payment choice and exploit quasi-experimental credit limit changes to quantify the welfare and default implications of real-time liquidity management.</p>
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
      <p>We investigate the underlying economic mechanisms that drive the usage patterns of the Early Wage Access (EWA) product documented using proprietary company data. We estimate the relative value of EWA under standard household preferences and identify the source for potential economic value for employees and employers.</p>
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
    <div class="research-note">Selected for the 2025 EWMES and 2025 Sydney Banking and Financial Stability Conference</div>
    <details class="abstract">
      <summary>Abstract</summary>
      <p>We exploit a segment of Chinese wealth management products (WMP) to isolate demand-side funding shocks from asset-side considerations, documenting a 60% pass-through of local inflation shocks to yields. We demonstrate that large banks' geographic footprint enables active, high-frequency liability reallocation across regions via internal capital markets, with greater yield response than smaller banks and significant cross-regional hedging behavior.</p>
    </details>
  </div>
  <div class="research-fig">
    <div class="fig-placeholder">Figure coming soon</div>
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
