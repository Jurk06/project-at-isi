---
layout: default
title: Water Well Riskiness Analysis
description: Analyzing the riskiness of water wells across India using advanced statistical methods at ISI Kolkata.
---

<section class="hero">
  <div>
    <div class="hero-badge">🏛️ ISI Kolkata &nbsp;·&nbsp; Data Science Research</div>
    <h1>Analysis of Water Well<br>Riskiness Across India</h1>
    <p class="hero-sub">
      A comprehensive data science study identifying high-risk wells, mapping regional patterns,
      and forecasting water scarcity using advanced statistical methods on the Atal Jal dataset.
    </p>
    <div class="hero-cta">
      <a href="#workflow" class="btn btn-primary">Explore Analysis ↓</a>
      <a href="{{ site.baseurl }}/about/" class="btn btn-outline">About the Project</a>
    </div>
  </div>
</section>

<div class="stats-row">
  <div class="stat-card">
    <div class="stat-num">29</div>
    <div class="stat-label">Indian States Analyzed</div>
  </div>
  <div class="stat-card">
    <div class="stat-num">5</div>
    <div class="stat-label">Analysis Modules</div>
  </div>
  <div class="stat-card">
    <div class="stat-num">MICE</div>
    <div class="stat-label">Imputation Method</div>
  </div>
  <div class="stat-card">
    <div class="stat-num">3</div>
    <div class="stat-label">Risk Clusters Identified</div>
  </div>
</div>

<div class="divider"></div>

<!-- ANALYSIS WORKFLOW -->
<section class="section" id="workflow">
  <div class="section-label">Research Pipeline</div>
  <h2 class="section-title">Five-Stage Analysis Workflow</h2>
  <p class="section-desc">
    Each step builds upon the last — from raw data through statistical testing, geographic mapping,
    imputation, trend analysis, and finally risk clustering.
  </p>

  <div class="analysis-grid">
    <a href="{{ site.baseurl }}/anova/" class="analysis-card">
      <div class="card-icon">📊</div>
      <div class="card-step">Step 01</div>
      <div class="card-title">ANOVA Analysis</div>
      <div class="card-desc">One-way ANOVA tests to detect statistically significant differences in well depth and water availability across Indian states.</div>
      <div class="card-arrow">Explore → </div>
    </a>

    <a href="{{ site.baseurl }}/visualization/" class="analysis-card">
      <div class="card-icon">🗺️</div>
      <div class="card-step">Step 02</div>
      <div class="card-title">Geographic Visualization</div>
      <div class="card-desc">Interactive Folium maps plotting all wells across India, color-coded by depth categories with regional pattern analysis.</div>
      <div class="card-arrow">Explore → </div>
    </a>

    <a href="{{ site.baseurl }}/imputation/" class="analysis-card">
      <div class="card-icon">🔧</div>
      <div class="card-step">Step 03</div>
      <div class="card-title">Missing Data Imputation</div>
      <div class="card-desc">Advanced MICE (Multiple Imputation by Chained Equations) techniques to handle missing values using data distribution patterns.</div>
      <div class="card-arrow">Explore → </div>
    </a>

    <a href="{{ site.baseurl }}/trends/" class="analysis-card">
      <div class="card-icon">📈</div>
      <div class="card-step">Step 04</div>
      <div class="card-title">Trend Analysis</div>
      <div class="card-desc">Historical water table depth trends over time to understand long-term decline patterns and predict future availability.</div>
      <div class="card-arrow">Explore → </div>
    </a>

    <a href="{{ site.baseurl }}/clustering/" class="analysis-card">
      <div class="card-icon">🔵</div>
      <div class="card-step">Step 05</div>
      <div class="card-title">Clustering Analysis</div>
      <div class="card-desc">Hierarchical clustering (Ward linkage) to identify distinct risk categories: High, Medium, and Low risk well groups.</div>
      <div class="card-arrow">Explore → </div>
    </a>

    <a href="{{ site.baseurl }}/about/" class="analysis-card">
      <div class="card-icon">👤</div>
      <div class="card-step">Context</div>
      <div class="card-title">About This Project</div>
      <div class="card-desc">Dataset details, research questions, methodology overview, and team information for this ISI Kolkata research project.</div>
      <div class="card-arrow">Read more → </div>
    </a>
  </div>
</section>

<div class="divider"></div>

<!-- KEY FINDINGS -->
<div class="findings-bg">
  <section class="section">
    <div class="section-label">Results</div>
    <h2 class="section-title">Key Findings</h2>
    <p class="section-desc">Critical insights from the analysis of India's water well data.</p>

    <div class="findings-grid">
      <div class="finding-card">
        <div class="finding-icon">🚨</div>
        <div class="finding-title">Significant Regional Variation</div>
        <div class="finding-text">ANOVA tests confirmed statistically significant differences in well depth across states, indicating diverse hydrological conditions.</div>
      </div>
      <div class="finding-card">
        <div class="finding-icon">📉</div>
        <div class="finding-title">Declining Water Tables</div>
        <div class="finding-text">Long-term trend analysis reveals critical patterns of water table decline in several states, raising urgent policy concerns.</div>
      </div>
      <div class="finding-card">
        <div class="finding-icon">🗄️</div>
        <div class="finding-title">Extensive Missing Data</div>
        <div class="finding-text">A significant portion of the dataset required advanced MICE imputation across three distinct missing data categories.</div>
      </div>
      <div class="finding-card">
        <div class="finding-icon">🔵</div>
        <div class="finding-title">Three Risk Clusters</div>
        <div class="finding-text">Hierarchical clustering identified three well risk groups: high-risk (deep, declining), medium-risk, and low-risk (stable, shallow).</div>
      </div>
    </div>
  </section>
</div>

<div class="divider"></div>

<!-- TECH STACK -->
<section class="section">
  <div class="section-label">Tools & Technologies</div>
  <h2 class="section-title">Built With</h2>
  <p class="section-desc">The full Python data science stack powering this analysis.</p>
  <div class="tech-list">
    <span class="tech-pill">🐍 Python 3</span>
    <span class="tech-pill">🐼 Pandas</span>
    <span class="tech-pill">🔢 NumPy</span>
    <span class="tech-pill">🤖 Scikit-learn</span>
    <span class="tech-pill">📊 Matplotlib</span>
    <span class="tech-pill">🎨 Seaborn</span>
    <span class="tech-pill">🗺️ Folium</span>
    <span class="tech-pill">📐 SciPy</span>
    <span class="tech-pill">📓 Jupyter</span>
    <span class="tech-pill">🌐 GitHub Pages</span>
    <span class="tech-pill">💎 Jekyll</span>
  </div>
</section>
