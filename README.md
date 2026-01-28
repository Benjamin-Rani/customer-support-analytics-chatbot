# customer-support-analytics-chatbot
AI-powered chatbot for analyzing customer support ticket data

**Project Overview**
1. This project is an AI-driven customer support analytics chatbot built using Python.
2. The chatbot analyzes customer support ticket data and answers business-related questions such as ticket volume, top complaint categories, and trends.
3. The project demonstrates how data analytics and basic AI logic can be combined to transform raw customer data into actionable insights.

**Business Problem**
1. Customer support teams receive thousands of tickets daily, making it difficult to quickly identify:
2. High-volume complaint categories
3. Recent spikes in support requests
4. Trends across companies or issue types
5. This chatbot helps simplify data exploration by allowing users to ask questions in plain language.

**What This Project Does**
Loads and cleans customer support ticket data (CSV)
Performs analytical calculations using Pandas
Uses rule-based NLP logic to interpret user questions
Returns numeric insights and visual charts

**Dataset**
Customer Support Chatbot Dataset (CSV)
Each row represents a customer support ticket.
**Key columns:**
. ticket_id – Unique ticket identifier
. created_at – Ticket creation date
. company – Company receiving the ticket
. category – Type of issue (Billing, Technical, Network, etc.)
. status – Ticket status (Resolved / Pending)
. customer_message – Customer complaint text

**Tools & Technologies**
. Python
. Pandas – Data cleaning & analysis
. Matplotlib / Seaborn – Data visualization
. Google Colab – Development environment

**Project Workflow**
**Data Loading**
Load CSV dataset into Google Colab

**Data Cleaning**
Handle missing values
Remove duplicates
Convert date columns to datetime format

**Analytics Functions**
Tickets opened in the last month
Top complaint categories
Ticket distribution by company

**Chatbot Logic**
Keyword-based query detection
Returns insights based on user input

**Visualization**
Generates charts for ticket trends

**Example Chatbot Queries**
1.“How many tickets were created last month?”
2.“What are the top complaint categories?”
3.“Show a chart of tickets by company”
