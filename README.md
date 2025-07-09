# Enhancing-Lead-Generation-with-AI-Insights
Caprae Capital – AI Readiness Assignment
Project Title: AI-Powered Lead Enrichment & Prioritization Engine
Candidate: Tejaswini Ramesh

 About This Assignment
This project was completed as part of Caprae Capital’s AI Readiness Internship challenge. The task was to enhance the functionality of a lead generation system like SaaSquatchLeads.com, by developing a lightweight but meaningful tool that improves how companies are surfaced, scored, and delivered for strategic review.
Caprae’s challenge encouraged either a Quality-First or Quantity-Driven approach. I deliberately chose the Quality-First strategy — and here’s why.

Why I Chose a Quality-First Approach
Scraping thousands of leads sounds impressive — but scraping alone doesn’t solve the real problem in modern outbound sales or M&A sourcing.
In real workflows, analysts and investors don't struggle with volume — they struggle with clarity.
They need to know:
Which leads are worth their time?
Which companies fit the firm’s thesis?
Why should this lead be prioritized over another?
I built a tool that doesn’t just generate data — it adds intelligence to it. Rather than building a new scraper, I simulated the post-scraping analyst layer — exactly the kind of work Caprae’s team would do after raw data comes in.
This is a tool that helps analyze leads, not just collect them.

Project Objective
“Enhance the quality and decision-readiness of lead data through AI-powered enrichment — helping analysts qualify and prioritize leads instantly.”

What the Tool Does
Given a basic dataset of companies (name, website, LinkedIn, location, size, revenue estimate), the tool performs the following steps:
🔹 Website & Brand Enrichment
Validates website status — checks if the website is live or down
Fetches logos — uses the Clearbit Logo API to generate professional visual icons for each lead
🔹 AI-Simulated Enrichment (Mimicking GPT Outputs)
Business Summary — short 1–2 line description of what the company does (manually simulated)
Business Tags — such as "SaaS", "Remote", "Productivity", "Bootstrapped", etc.
Analyst Notes — strategic insight or recommendation, such as:
“High NPS and strong PLG traction; ideal for bundling or expansion into B2B verticals.”
Lead Score (0–100) — custom logic to assign numeric value based on product fit, maturity, and potential
These fields reflect what a GPT-4 powered pipeline or in-house analyst might produce with additional data context.

Visual Insights
Bar Chart of Lead Scores — shows priority companies at a glance
Tag Frequency Chart — surfaces dominant company themes
CSV Export — all enriched data exported for use in CRM, Excel, Power BI, or internal tools

How It Works – Step-by-Step
Data Preparation
Created a dummy dataset of 4 real-world SaaS companies with public data: Canny, Notion, Linear, Webflow
Web Status Check
Used the requests library to verify if each company’s site is live
Logo Fetching
Used clearbit.com logo API by extracting domain names
Manual GPT Simulation
Enriched each lead with:
A 1–2 line business summary
A set of tags (keywords)
An analyst note
A lead score (0–100)
Data Visualization
Used matplotlib and seaborn to create intuitive charts:
Horizontal bar graph of lead scores
Business tag frequency distribution
Export
Final enriched data is saved as final_enriched_leads.csv

 Visual Outputs
1.Bar Chart of Scores — instantly shows highest potential leads
2. Tag Frequency Plot — reveals vertical trends in your pipeline
3. Clean Output DataFrame — structured for CRM or analysis
These insights are the kind that help an analyst act fast — not just read a spreadsheet.

Business Relevance to Caprae
This tool was built with Caprae’s core values in mind:

Caprae Value	How This Project Reflects It
1. Independent Thinking	Chose insight over scale; questioned assumptions about scraping
2. AI + Strategy Focus	Designed a pipeline that mimics GPT output and strategic analysis
3. Founder/Operator Mindset	Built for real workflow integration — CRM-ready output
4. Creativity	Went beyond scraping — into scoring, tagging, summarizing, and visualizing
5. Usefulness	Analysts can filter, score, and discuss leads immediately from output

 Tools Used
Python
Jupyter Notebook
Pandas
Matplotlib / Seaborn
Requests (HTTP check)
Clearbit Logo API

Final Thoughts
This project was built in just under 1 hour, with a deliberate focus on quality over quantity. Instead of spending time building another scraping tool, I focused on what actually drives decision-making: context, clarity, and prioritization.
In that time, I was able to simulate what an AI assistant or analyst would do — turning basic company data into structured, actionable insights.
This tool reflects my ability to move quickly, think strategically, and align with Caprae’s vision of leveraging AI to empower analysts and operators.
Thank you for the opportunity to showcase both what I can build and how I approach challenges.
