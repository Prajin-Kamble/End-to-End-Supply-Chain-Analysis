# End-to-End-Supply-Chain-Analysis

## 1. Business Problem Statements
AtliQMart is a Gujarat-based organic food manufacturing company that operates with a limited product portfolio but has successfully disrupted the market in two Indian cities. Recently, the company expanded operations to a third city—New Jersey, USA.<br>

Despite strong demand, AtliQMart’s supply chain maturity is low, resulting in:<br>
•	Poor order fulfillment performance<br>
•	Inconsistent deliveries to supermarket customers<br>
•	Customer dissatisfaction due to incomplete and delayed orders<br>

As the company plans to scale further, these issues pose a high business risk. The leadership required a data-driven and AI-enabled solution to identify bottlenecks and improve supply chain reliability.

## 2. Project Description
This is an end-to-end supply chain analytics project designed to simulate a real-life FMCG supply chain scenario using dummy data.<br>

### The project covers:
•	Automated data ingestion from operational sources<br>
•	Centralized storage using PostgreSQL<br>
•	KPI-based supply chain performance evaluation<br>
•	Advanced analysis using Quadratic AI<br>
•	Business-oriented insights and recommendations<br>

Unlike static reporting, this solution introduces AI-powered analytics with automated workflows, making it scalable and future-ready.

## 3. Goal of the Analysis
### The primary objectives of this project were:
•	Identify reasons behind poor order fulfillment<br>
•	Measure supply chain performance using industry-standard KPIs<br>
•	Detect gaps in inventory planning and order management<br>
•	Provide actionable insights to improve customer satisfaction<br>
•	Propose an AI-enabled, automated analytics solution suitable for scaling<br>

![N8N Autiomation Snapshot Preview](https://github.com/Prajin-Kamble/End-to-End-Supply-Chain-Analysis/blob/main/N8N%20Automation%20Snapshot.PNG)

## 4. Tech Stack (Technical Skills & AI Tools)
### 🔧 Technical Skills
1. Excel – Quick insights, KPI summaries <br>
2. SQL (PostgreSQL) – Data modeling, joins, aggregations<br>
3. Data Cleaning & Transformation<br>
4. Supply Chain Domain Knowledge<br>

### 🤖 AI & Automation Tools
1. n8n – Workflow automation and data pipelines<br>
2. Gmail Integration – Automated data extraction<br>
3. Supabase – PostgreSQL database hosting<br>
4. Quadratic AI – AI-assisted spreadsheet analytics and Python execution<br>

## 5. Important KPIs Tracked
### The following core supply chain KPIs were calculated and analyzed:
1. Total Orders - Number of unique customer orders<br>
2. Total Order Lines - Total line items requested<br>
3. Line Fill Rate (%) -	% of order lines fulfilled<br>
4. Volume Fill Rate (%) -	% of ordered quantity shipped<br>
5. On-Time Delivery (%) -	Orders delivered within promised time<br>
6. In-Full Delivery (%)	- Orders delivered with full quantity<br>
7. OTIF (%)	- Orders delivered both on time and in full<br>

OTIF was treated as the most critical KPI, representing customer-level reliability.<br>

![Quadratic AI KPI Summary Table Preview](https://github.com/Prajin-Kamble/End-to-End-Supply-Chain-Analysis/blob/main/Analysis%20Snapshot%20of%20Quadratic.PNG)

## 6. Key Insights & Business Impact
### 🔍 Key Insights
1. Line Fill Rate (63.3%) is significantly low → frequent line-item failures<br>
2. Volume Fill Rate (96.6%) is high → quantity issues are minimal<br>
3. On-Time Delivery (57.8%) is poor → logistics & planning gaps<br>
4. In-Full Delivery (51.2%) indicates inventory mismatch<br>
5. OTIF (28.0%) is critically low → major customer dissatisfaction risk<br>

### 📉 Business Impact
1. Supermarkets lose trust due to unreliable deliveries<br>
2. Risk of contract loss during expansion<br>
3. High operational inefficiencies<br>
4. Reactive firefighting instead of proactive planning<br>

## 7. Final Recommendations
### 1. Inventory Optimization
•	Maintain safety stock for high-moving SKUs.<br>
•	Segment products based on demand volatility.<br>

### 2. Logistics & Planning
•	Improve delivery scheduling accuracy.<br>
•	Strengthen coordination between warehouse and distribution teams.<br>

### 3. AI-Driven Improvements
•	Use Quadratic AI for continuous KPI monitoring.<br>
•	Automate daily/weekly performance checks.<br>
•	Implement alert systems for OTIF breaches.<br>

### 4. Management Reporting
•	Shift focus from Volume Fill Rate to OTIF.<br>
•	Use dashboards for proactive decision-making.<br>
•	Enable leadership with real-time visibility.<br>
