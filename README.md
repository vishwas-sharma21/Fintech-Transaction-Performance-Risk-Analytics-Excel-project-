<h1 align="center">📊 Fintech Transaction Performance & Risk Analytics</h1>
<h3 align="center">Excel Dashboard | Business Analytics</h3>

<p align="center">
  <b>Analyzing transaction performance, failure trends, and financial leakage using Excel</b>
</p>

<hr>

<h2> Project Overview</h2>
<p>
This project analyzes <b>online transaction data for 2023 and 2024</b> to evaluate business performance,
identify risk areas, and measure financial leakage caused by cashback incentives.
</p>

<p>
The dashboard is designed to simulate a <b>real-world fintech analyst use case</b>, focusing on KPI tracking,
trend forecasting, and actionable business insights.
</p>

<hr>

<h2> Business Problem</h2>
<p>
Fintech platforms often struggle with:
</p>
<ul>
  <li>Increasing transaction failures</li>
  <li>Uncontrolled cashback spending</li>
  <li>Declining profitability per transaction</li>
</ul>

<p>
This project answers:
</p>
<ul>
  <li>Is transaction growth actually profitable?</li>
  <li>Where are failures happening?</li>
  <li>Are incentives (cashbacks) hurting revenue?</li>
</ul>

<hr>

<h2>📊 Key KPIs Designed</h2>
<ul>
  <li><b>Transaction Volume</b> – Total number of transactions</li>
  <li><b>Failure Rate</b> – % of failed transactions</li>
  <li><b>Leakage Cost</b> – Total cashback amount (financial loss)</li>
  <li><b>Net Contribution</b> = Transaction Fees − Cashback</li>
</ul>

<p><b>Special Features:</b></p>
<ul>
  <li>Conditional formatting (Green = Positive, Red = Negative)</li>
  <li>Year-over-Year comparison (2024 vs 2023)</li>
  <li>Visual indicators (↑ ↓ arrows for performance tracking)</li>
</ul>

<hr>

<h2>📈 Dashboard Components</h2>

<h3>1. Transaction Volume Trend + Forecast</h3>
<ul>
  <li>Line chart showing growth from 2023 → 2024</li>
  <li>Forecast for 2025 using <b>FORECAST.LINEAR()</b></li>
</ul>

<h3>2. Transaction Fees vs Cashback</h3>
<ul>
  <li>Side-by-side column chart</li>
  <li>Shows profitability imbalance</li>
</ul>

<h3>3. Top 5 Product Category Expense</h3>
<ul>
  <li>Funnel chart ranking highest spending categories</li>
</ul>

<h3>4. Failure Rate by Payment Method</h3>
<ul>
  <li>Bar chart showing % failure distribution</li>
  <li>Identifies highest-risk payment channels</li>
</ul>

<h3>5. Loss Per Transaction</h3>
<p>
<b>Formula:</b><br>
Loss Per Transaction = Net Contribution / Total Transactions
</p>
<ul>
  <li>Shows profitability trend per transaction</li>
  <li>Indicates rising financial leakage</li>
</ul>

<hr>

<h2>🎛️ Interactivity</h2>
<ul>
  <li><b>Slicers:</b> Location (Rural, Urban, Suburban)</li>
  <li><b>Slicers:</b> Month-wise filtering</li>
</ul>

<hr>

<h2>🔍 Key Insights</h2>
<ul>
  <li>📈 Transaction volume expected to reach <b>~4500 in 2025</b></li>
  <li>📉 Failure rate projected to decline to <b>~2.9%</b></li>
  <li>⚠️ Cashback payouts are <b>higher than transaction fees</b></li>
  <li>💳 Credit cards show the <b>highest failure rate</b></li>
</ul>

<h3> Business Implication</h3>
<p>
<b>Growth is not translating into profitability.</b><br>
Increasing transactions may lead to higher <b>financial leakage</b> unless the cashback strategy is optimized.
</p>

<hr>

<h2> Analytical Approach</h2>
<ul>
  <li>Data cleaning and validation</li>
  <li>KPI engineering with business logic</li>
  <li>Year-over-year comparison</li>
  <li>Trend analysis and forecasting</li>
  <li>Performance vs cost evaluation</li>
</ul>

<hr>

<h2>⚙️ Tools & Skills Used</h2>
<ul>
  <li>Microsoft Excel</li>
  <li>Pivot Tables & Charts</li>
  <li>Dashboard Design</li>
  <li>Conditional Formatting</li>
  <li>FORECAST.LINEAR</li>
  <li>Business Analysis</li>
</ul>

<hr>

<h2 align="center">📊 Dashboard Preview</h2>

<p align="center">
  <img src="Dashboard Image/Excel Dashboard.png" width="900">
</p>

<p align="center">
  📥 <a href="Dashboard/Fintech Transaction Performance and Risk Analytics.xlsx"><b>Download Interactive Dashboard</b></a>
</p>
<hr>

<h2>📁 Project Structure</h2>

<pre>
📦 fintech-transaction-analysis
 ┣ 📂 data
 ┃ ┗ digital_wallet_transactions.csv
 ┣ 📂 dashboard
 ┃ ┗ Fintech Transaction Performance and Risk Analytics.xlsx
 ┣ 📂 screenshots
 ┃ ┗ dashboard.png
 ┣ README.md
</pre>

<hr>

<h2>▶️ How to Use</h2>
<ol>
  <li>Download the repository</li>
  <li>Open the Excel dashboard file</li>
  <li>Use slicers to filter data</li>
  <li>Analyze KPIs and trends</li>
</ol>

<hr>


<p align="center">⭐ If you found this project useful, consider starring the repo!</p>
