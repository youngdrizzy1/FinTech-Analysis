# FINTECH ANALYSIS

## Table of Content
- [Project Overview](#Project-Overview)
- [Tools](#Tools)
- [Workflow](#Workflow)
- [Insights](#Insights)

## Project Overview
This project analyzes Nigeria’s FinTech market to provide data-driven insights for a startup looking to refine its product offerings, pricing strategy, target customer segmentation, and marketing approach. The goal is to understand user preferences, financial behavior, and economic status to help the startup optimize its services and reach the right audience effectively.

## Tools
### Data Processing & Analysis
- Python (Pandas, NumPy): Data generation and manipulation

### Data Visualization & Interpretation
- Power BI: Interactive dashboards for market trends, pricing structures, and customer segmentation.

### Research
- CBN & NBS Reports: Official statistics on financial inclusion, income distribution, and digital finance adoption.
- Industry Research & FinTech Websites: Insights into services, pricing models, and consumer behavior from platforms like Flutterwave, Paystack, OPay, Kuda, and Carbon.

## Workflow
### Research & Data Collection
- Survey (20 People): Conducted a small survey to gather initial insights on:
 - Demographics (Age, Gender, Employment, Income Level).
 - Financial Literacy (Understanding of banking, investments, and budgeting).
 - Preferred FinTech Services (Mobile banking, digital payments, micro-loans).
 - Service Delivery Preferences (Self-service vs. agent banking).

- CBN & NBS Reports → Used official financial inclusion data to ensure realistic income levels, banking adoption rates, and digital transaction trends.

- Industry Research & FinTech Websites → Analyzed pricing structures, services, and customer trends from leading Nigerian FinTech firms

### Data Generation & Processing:
- Dataset Creation (200,000 Rows): Based on survey insights and official statistics, a synthetic dataset was generated using Python (NumPy, Pandas).

- Realistic Data Distributions: Ensured accuracy in:
 - Age Groups (Weighted toward middle-aged users for better representation).
 - Income Levels & Employment (Aligned with Nigerian economic data).
 - Financial Literacy (Classified as Low, Basic, Intermediate, Advanced, or Expert).
 - Business Ownership Segments (Young Professionals, Urban Professionals, Small Business Owners, Rural Users).
 - Service Preferences (Mobile App, Web Platform, or Agent Banking)

### Data Analysis & Visualization
- Visualized trends and patterns using line charts, bar charts, pie chart etc.

## Insights
### 1. Financial Literacy Level & Service Preference
- Low: 72.98% rely on Agent Banking, showing dependence on intermediaries.
- Medium: More balanced use of Mobile Apps (37.31%) and Web Platforms (27.84%).
- High: More self-reliant, with 51.91% using Mobile Apps and 30.09% using Web Platforms.

  ![1](https://github.com/user-attachments/assets/1e2d587b-4717-4287-8e2a-1ce9a12005c0)

### 2. Age Group by Number of FinTech Users
- Young Adults (94K users) form the largest segment of FinTech users.
- Adults (71K users) are the second-largest group.
- Middle-Aged (21K users) and Aged (14K users) have significantly lower adoption.

  ![2](https://github.com/user-attachments/assets/b2aa1798-5fb1-4096-a9a4-93dfe7c16779)

### 3. FinTech Users by Target Customers
- Young Urban Professionals (80K users) form the largest segment of FinTech users.
- Urban Professionals (70K users) are the second-largest group.
- Small Business Owners (30K users) and Rural Users (20K users) have significantly lower adoption.

  ![3](https://github.com/user-attachments/assets/9ae15cb5-21e0-45a1-94f3-6f7ebb2afc02)

### 4. Number of FinTech User by Location
- Urban users (170.94K, 85.47%) form the overwhelming majority of FinTech users.
- Rural users (29.06K, 14.53%) have significantly lower adoption.

  ![4](https://github.com/user-attachments/assets/234c28d8-e02f-4f52-9169-9f081049ed97)

### 5. Financial Literacy Level & User Base
- High literacy: 118K users, the largest segment.
- Medium literacy: 57K users, showing a moderate engagement.
- Low literacy: 25K users, the smallest group.

  ![5](https://github.com/user-attachments/assets/d9b6b757-dc7a-40aa-829c-27ee37d149a4)

### 6. Income Level by Number of FinTech Users
- High-income users: 50.40% are Urban Professionals, while 49.60% are Young Urban Professionals.
- Middle-income users: 42.70% are Young Urban Professionals, followed by 27.92% Urban Professionals, 24.06% Small Business Owners, and 5.32% Rural Users.
- Low-income users: 57.02% are Rural Users, and 42.98% are Small Business Owners.

  ![6](https://github.com/user-attachments/assets/1bab4002-d0f1-4506-9a23-e3c566917c23)

### 7. Gaps in Competitive Pricing
- Many FinTech companies offer competitive pricing, but only a few provide user benefits.
- Binance offers Trading Discounts, Kuda has Loyalty Rewards, while OPay and Roqqu provide Cashback.
- Several companies (Flutterwave, Interswitch, Luno, Moniepoint, Paystack) offer no additional user benefits.

  ![7](https://github.com/user-attachments/assets/5006ecca-3bfd-4bc3-90c8-4566e2862a4b)

### 8. Gaps in Value-Based Pricing
- Several FinTech companies use a value-based pricing strategy, but their user benefits vary.
- Companies like CowryWise and PiggyVest offer free tools, while FairMoney provides cashback.

  ![8](https://github.com/user-attachments/assets/0857a3e0-4654-4655-98a7-193fd912557b)

### 9. Distribution of Pricing Strategies
- The majority (90.45%) of FinTech companies use Competitive Pricing, while only 9.55% use Value-Based Pricing.
- This suggests that most companies prioritize market competition over customer-perceived value.

  ![9](https://github.com/user-attachments/assets/1d475435-25a9-41b6-b593-fc9f7c97c070)

### 10. Preferred FinTech Products by Users
- Digital Payments (85K users) and Mobile Banking (82K users) are the most preferred FinTech products.
- Micro-Lending (20K users) and Blockchain (13K users) have significantly fewer users, suggesting lower adoption.

  ![10](https://github.com/user-attachments/assets/0e6d76fa-65c4-411f-9a10-17a955c9abff)

### 11. Fintech Product Familiarity by Users
- Digital payments are the most well-known, with 43K experts and 25K novice users.
- Mobile banking has the highest novice user base (49K), indicating high adoption among beginners.
- Blockchain has the lowest user familiarity (6K experts, 1K novices).

  ![11](https://github.com/user-attachments/assets/348f7946-ab82-4165-89f8-46e68438f81c)

### 12. Customer Satisfaction Levels
- Young urban professionals report the highest satisfaction (79.99% high, 20.01% moderate).
- Urban professionals also show high satisfaction (70.22% high).
- Small business owners have moderate satisfaction (49.72%), with 20.07% low satisfaction.
- Rural users report the lowest satisfaction (69.93% low satisfaction).

  ![13](https://github.com/user-attachments/assets/de110582-de4a-4eb8-84a3-0fd5fa6a59ea)

### 13. Fintech Companies and Their Products
- Digital payments and mobile banking are the most common fintech offerings.
- Blockchain-based companies (Binance, Luno, Roqqu, Flutterwave) are fewer in number.
- Micro-lending is a niche market with only a few players.

  ![14](https://github.com/user-attachments/assets/9f02b6b9-9ab9-435d-874c-36d6bfcd927c)

### 14. Financial Literacy and Fintech Usage
- Young Urban Professionals have the highest number of fintech users (80K), with a majority having high financial literacy (56K) and medium literacy (24K).
- Urban Professionals have the same number of highly literate users (56K) but fewer medium-literate users (14K), totaling 70K.
- Small Business Owners have 30K users, with a more balanced split among financial literacy levels: 15K medium, 9K low, and 6K high.
- Rural Users have the lowest fintech usage (20K), with most having low financial literacy (16K) and very few having medium literacy (4K).

  ![15](https://github.com/user-attachments/assets/0d0721f2-292c-4970-95f4-dccdf4143f3b)

### 15. Transaction Volume
- Young Urban Professionals conduct the highest transaction volume at 80K.
- Urban Professionals follow with 70K transactions.
- Small Business Owners account for 30K transactions.
- Rural Users contribute the least, with only 20K transactions.
