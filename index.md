---
layout: default
title: Fei Wang
---

<div class="container-fei">

<!-- Navigation -->
<div class="nav-fei">
  <a href="#about">About</a>
  <a href="#projects">Projects</a>
  <a href="#skills">Skills</a>
  <a href="#contact">Contact</a>
</div>

<!-- HERO -->
<section class="hero">
  <div>
    <h1>Fei Wang</h1>
    <p class="subtle">Data & Business Analytics — SQL • Power BI • Tableau • Python</p>
    <p>Based in Ontario, Canada</p>

    <div class="badgebar">
      <span class="badge">SQL</span>
      <span class="badge">Power BI (DAX)</span>
      <span class="badge">Tableau</span>
      <span class="badge">Python (Pandas, scikit-learn)</span>
      <span class="badge">Excel (Power Query)</span>
    </div>

    <p style="margin-top:14px">
      I turn messy business data into decisions people can act on. My work ranges from **sales & customer analytics** (RFM, cohorts, market basket) to **credit-risk modeling** and **interactive BI dashboards** for non-technical stakeholders.
    </p>
  </div>

  <div>
    <img src="{{ site.baseurl }}/assets/hero-placeholder.png" alt="Analytics dashboard preview" style="width:100%; border-radius:16px; border:1px solid var(--border);" />
    <p class="subtle" style="margin-top:6px">Preview — sample dashboard tiles (Power BI / Tableau)</p>
  </div>
</section>

<!-- ABOUT -->
<section id="about" class="section">
  <h2>About Me</h2>
  <p>
    I’m transitioning into data and analytics with a background in <strong>IT support</strong>, <strong>business analysis</strong>, and <strong>operations</strong>.
    I like clean data models, fast queries, and visuals that make sense to busy people.
  </p>

  <ul>
    <li>Cleaned & modeled datasets for reporting (Excel, SQL Server, Power BI)</li>
    <li>Built dashboards for sales, customer behavior, and product performance</li>
    <li>Collaborated with stakeholders to explain insights in plain language</li>
  </ul>

  <p><em>Tech I use:</em> SQL, Power BI (DAX, parameters, slicers), Tableau, Python (data prep & ML), Excel (Power Query, VLOOKUP, Pivot).</p>
</section>

<!-- PROJECTS -->
<section id="projects" class="section">
  <h2>Featured Projects</h2>

  <div class="grid">

    <div class="card">
      <h3>Retail Sales & Customer Insights (Power BI)</h3>
      <p><strong>Goal:</strong> Understand profit drivers, territory performance, reseller quality, RFM segments, and cross-sell opportunities.</p>
      <ul>
        <li>Star schema (FactSales ↔ Product, Customer, Reseller, Territory, Date)</li>
        <li>DAX: profit margin, period-over-period trends, segmentation (RFM)</li>
        <li>Market basket analysis & Pareto for bundle/upsell recommendations</li>
      </ul>
      <p><strong>Business value:</strong> Identify high-margin regions & products, underperforming resellers, and retention targets.</p>
      <div class="tags">
        <span class="tag">Power BI</span><span class="tag">DAX</span><span class="tag">RFM</span><span class="tag">MBA</span>
      </div>
      <p><a href="YOUR_POWERBI_LINK" target="_blank">View dashboard →</a></p>
    </div>

    <div class="card">
      <h3>Credit Risk Model (Python & ML)</h3>
      <p><strong>Goal:</strong> Predict loan default for risk screening.</p>
      <ul>
        <li>Preprocessing: null handling, encoding, binning; train/test + class balancing</li>
        <li>Models: Logistic Regression, Random Forest, LightGBM</li>
        <li>Evaluation: ROC curve, feature importance; ~0.62 test accuracy on 200k row slice</li>
      </ul>
      <p><strong>Learning:</strong> Imbalanced classification workflow & feature engineering.</p>
      <div class="tags">
        <span class="tag">Python</span><span class="tag">scikit-learn</span><span class="tag">LightGBM</span>
      </div>
      <p><a href="YOUR_GITHUB_REPO_FOR_MODEL" target="_blank">Code & notebook →</a></p>
    </div>

    <div class="card">
      <h3>Rental Market Web Scraper & Price Analysis</h3>
      <p><strong>Goal:</strong> Scrape listings and analyze fair rent by area.</p>
      <ul>
        <li>Requests/BeautifulSoup → price, location, bed/bath, description</li>
        <li>Cleaning: deduping, outlier removal; Pandas pipeline</li>
        <li>Dashboard: price by neighborhood & bedroom count</li>
      </ul>
      <div class="tags">
        <span class="tag">Python</span><span class="tag">Pandas</span><span class="tag">Tableau/Power BI</span>
      </div>
      <p><a href="YOUR_REPO_OR_DASHBOARD_LINK" target="_blank">See code / viz →</a></p>
    </div>

    <div class="card">
      <h3>SQL Analytics Mini-Library</h3>
      <p><strong>Examples:</strong> customer segmentation & campaign performance, credit limit monitoring, movie rental behavior.</p>
      <ul>
        <li>Joins across normalized tables, CTEs, window functions</li>
        <li>Case logic for groups; parameterized filtering</li>
      </ul>
      <div class="tags"><span class="tag">SQL</span><span class="tag">CTEs</span><span class="tag">Windows</span></div>
      <p><a href="YOUR_SQL_SNIPPETS_REPO" target="_blank">View queries →</a></p>
    </div>

  </div>
</section>

<!-- SKILLS -->
<section id="skills" class="section">
  <h2>Skills</h2>
  <ul>
    <li><strong>Data / Analytics:</strong> SQL, Power BI (data modeling, DAX), Tableau, Excel (Power Query, PivotTables)</li>
    <li><strong>ML / Python:</strong> Pandas, scikit-learn, LightGBM, evaluation (ROC, AUC, feature importance)</li>
    <li><strong>Ops / Scripting:</strong> Bash (Ubuntu), PowerShell (Windows)</li>
    <li><strong>Communication:</strong> translating data into clear business stories for busy stakeholders</li>
  </ul>
</section>

<!-- CONTACT -->
<section id="contact" class="section">
  <h2>Contact</h2>
  <p>Let’s connect.</p>
  <ul>
    <li><a href="https://www.linkedin.com/in/YOUR-LINKEDIN">LinkedIn</a></li>
    <li><a href="https://github.com/YanfeiWang3973">GitHub</a></li>
    <li><a href="https://app.powerbi.com/view?r=eyJrIjoiMWNjN2QwOWEtZDIzNy00NWU1LWE1ZGItODg2MTAyZTkwNWFkIiwidCI6IjZmMGJiNzJmLTUzNzctNGRkZi05MzZhLWI2YzcyYmYyMWFlMiIsImMiOjF9" target="_blank">Power BI Portfolio</a></li>
    <li><a href="https://public.tableau.com/app/profile/YOUR_TABLEAU" target="_blank">Tableau Public</a></li>
  </ul>
</section>

<footer class="footer-fei">
  <span class="subtle">© {{ "now" | date: "%Y" }} Fei Wang</span>
  <span class="subtle">Built with Jekyll + GitHub Pages</span>
</footer>

</div>

