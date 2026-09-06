# Ex.No.10
Content Creation (Reports, Articles, Case Studies, etc.) Using Prompt Patterns

## Date:
## Reg. No.

## Aim:
To demonstrate how various prompting techniques (query decomposition, decision-making, semantic filtering, etc.) can be employed to create content such as reports, articles, case studies, or creative works like comic books, using ChatGPT or similar models. The objective is to highlight how different prompt structures affect the content's quality, coherence, and structure.

## Procedure:
1.	Introduction to Prompt Patterns: Begin by understanding the following prompt patterns:
○	Query Decomposition: Breaking down complex queries into smaller, actionable parts.
○	Decision Making: Asking the model to choose between options or directions.
○	Answer Engineering: Refining outputs by giving detailed instructions on how to structure or format the answer.
○	Fact Check List: Ensuring the content is factually accurate, especially for reports or case studies.
○	Tail Generation: Extending the content logically to create depth in storytelling or analysis.
○	Menu Actions: Presenting multiple action choices and guiding the AI to select one.
○	Semantic Filter: Applying filters to control the tone, style, and accuracy of the content.
2.	Choosing the Content Type: Decide on the type of content you want to create. This could be:
○	Reports (e.g., industry analysis, sustainability reports, etc.)
○	Case Studies (e.g., business solutions, technological innovations)
○	Articles (e.g., opinion pieces, educational articles)
○	Creative Content (e.g., comic book story, short stories, video scripts)
3.	For example, you could choose a business report on market trends, a case study on a successful startup, or even a story-based prompt like creating a fictional world for a comic.
4.	Creating the Prompts:
○	Start with simple prompts to generate initial content.
○	Gradually refine the prompts, moving toward more complex techniques like decision-making (asking the model to pick one of several options), tail generation (extending the narrative), and semantic filtering (adjusting style or tone).
5.	Generating and Refining Outputs: Use the model to generate initial drafts, and then refine the outputs using iterative adjustments:
○	For a report, prompt the model with basic data, then ask for a deeper analysis and insights.
○	For creative content, refine the initial story idea with specific details on characters, settings, or actions.
6.	Review and Evaluation: After generating content, evaluate the outputs for:
○	Coherence: Is the generated content logical and structured?
○	Creativity/Originality: Is the content engaging and fresh?
○	Accuracy: Is the content factually accurate (for reports and case studies)?
○	Tone and Style: Does the content match the intended tone (formal, creative, educational)?
________________________________________
Test Case Scenarios for Content Generation: (USE ANY 2)
content generation scenarios:
1.	Business Report on Market Trends
2.	Case Study on Business Success
3.	Article on Climate Change
4.	Creative Writing - Sci-Fi Short Story
5.	Educational Report on Renewable Energy
6.	Product Launch Announcement
7.	Travel Blog Post
8.	Research Paper on Artificial Intelligence
9.	Interview Transcript for Documentary
10.	Sustainability Practices in Fashion
11.	How to Build an E-commerce Website
12.	Social Issue Awareness Campaign
13.	Artificial Intelligence Impact on Healthcare
## Instructions:
1.	Select a Topic: Choose a topic (e.g., market trends, climate change, sci-fi story) that interests you.
2.	Use Basic Prompts: Start by crafting simple, general prompts to generate initial content.
3.	Refine Your Prompts: Gradually introduce more complexity by adding details, refining the structure, and using different prompt techniques like decision making or semantic filtering.
4.	Evaluate the Output: Review the generated content for clarity, creativity, and accuracy.
5.	Iterate for Improvement: Based on the feedback, refine the prompts and regenerate the content as needed.

## Deliverables:
1.	First Draft: A basic draft of the report, case study, article, or story generated using simple prompts.
2.	Refined Content: A more detailed and structured output, achieved by applying more advanced prompt techniques.
3.	Multiple Versions: Different versions of the content, showing the effect of prompt changes on the output.
4.	Final Version: The polished version of the content after incorporating feedback and refining the prompts.
## prompt:
# ROLE

Act as a senior Python developer, Generative AI engineer, automation engineer, UI/UX developer, and project mentor.

I am building a real-world college project called:

**AI-Powered Multi-Platform Content Generation and Automation System**

I want you to help me develop this project step by step in VS Code.

Do NOT generate the entire project at once. Build it incrementally, test each stage, explain errors, and only move to the next stage after the current stage works.

---

# PROJECT OBJECTIVE

Build a Streamlit-based AI application that accepts one campaign/event/product/topic as input and generates platform-specific content.

The system should be able to generate:

1. Email
2. LinkedIn post
3. Instagram caption
4. Blog
5. Article
6. Report
7. Hashtags
8. Short promotional content

The system should eventually support:

**Input → AI Generation → Preview → Edit → Human Approval → Scheduling → Publishing → Analytics → AI Recommendations**

The system should be designed as a real-world project rather than a simple text generator.

---

# CURRENT TECHNOLOGY STACK

Use:

* Python
* Streamlit
* Pandas
* Plotly
* SQLite initially
* Python-dotenv
* LLM API
* REST APIs
* n8n/Make/Zapier for automation where appropriate
* AWS as an optional deployment platform

Do not introduce unnecessary technologies.

Keep the initial implementation simple and beginner-friendly, but structure the project so that it can later be extended.

---

# CURRENT PROJECT STRUCTURE

I have already created:

AI_Content_Automation/

```
app.py
requirements.txt
.env

modules/
    content_generator.py
    email_generator.py
    social_generator.py
    blog_generator.py
    report_generator.py

database/
    database.py

data/
    campaigns.csv

assets/
```

I also have a Python virtual environment called:

venv/

Streamlit is already installed.

---

# CURRENT DEVELOPMENT STATUS

The project folder has already been created.

The folder structure has already been created.

The Python virtual environment has already been created.

Streamlit is already installed.

I have also created an initial Streamlit dashboard in app.py.

The current dashboard contains:

* Project title
* Topic input
* Target audience input
* Tone selection
* Content type selection
* Generate button

The current dashboard only collects user input.

The AI model is NOT connected yet.

Therefore, the next step is to connect the AI engine.

---

# MAIN PROJECT WORKFLOW

The final application should follow this architecture:

USER

↓

STREAMLIT DASHBOARD

↓

CAMPAIGN INPUT

* Topic
* Description
* Target audience
* Tone
* Language
* Date
* Goal
* Keywords
* Selected platforms

↓

AI CONTENT GENERATION ENGINE

↓

PLATFORM-SPECIFIC CONTENT

* Email
* LinkedIn
* Instagram
* Blog
* Article
* Report

↓

HUMAN REVIEW

↓

EDIT

↓

APPROVE

↓

SCHEDULE

↓

PUBLISH

↓

ANALYTICS

↓

AI PERFORMANCE REPORT

↓

AI RECOMMENDATIONS

---

# EXAMPLE USE CASE

Use this example throughout development when testing:

Topic:

"AI & Cloud Computing Workshop"

Audience:

"College Students"

Date:

"15 September 2026"

Tone:

"Professional"

Goal:

"Increase registrations"

Platforms:

Email, LinkedIn, Instagram, Blog

The system should generate different content for each platform.

Do not simply copy the same paragraph across platforms.

---

# PLATFORM REQUIREMENTS

## EMAIL

Generate:

* Subject
* Greeting
* Introduction
* Main message
* Event/product details
* Call to action
* Closing

The email should be professional and readable.

---

## LINKEDIN

Generate:

* Strong opening
* Professional content
* Key benefits
* Call to action
* Relevant hashtags

---

## INSTAGRAM

Generate:

* Short engaging caption
* Emojis where appropriate
* Call to action
* Relevant hashtags

---

## BLOG

Generate:

* SEO-friendly title
* Introduction
* Headings
* Main content
* Examples
* Conclusion
* FAQ
* Keywords
* Meta description

---

## ARTICLE

Generate:

* Title
* Introduction
* Sections
* Examples
* Conclusion

Use a more informative style than Instagram or LinkedIn.

---

## REPORT

Generate:

* Executive summary
* Key metrics
* Important findings
* Performance analysis
* Recommendations

The report should be based on supplied data when data is available.

Do NOT invent analytics data.

---

# AI CONTENT ENGINE

Create a reusable AI generation architecture.

The content generator should receive:

* topic
* description
* audience
* tone
* language
* platform
* content requirements

and return structured content.

Prefer structured output such as JSON when appropriate so that the Streamlit application can reliably display different content sections.

The architecture should allow different prompts/templates for:

* email
* LinkedIn
* Instagram
* blog
* article
* report

---

# ENVIRONMENT VARIABLES

Never hard-code API keys inside Python files.

Use:

.env

for secrets.

The .env file should be excluded from Git.

Create an appropriate .gitignore file if needed.

Explain how to configure the API key safely.

---

# DEVELOPMENT RULES

Follow these rules:

1. Do NOT generate the complete application at once.
2. Work one milestone at a time.
3. Before giving code, explain what we are building.
4. Give the exact filename where each code section should go.
5. Give complete code for the file being modified.
6. Explain exactly where to paste the code.
7. Give the exact terminal command to run.
8. Tell me what output I should expect.
9. If there is an error, help me debug it before moving forward.
10. Avoid unnecessary dependencies.
11. Keep the code beginner-friendly.
12. Use functions and modular architecture.
13. Do not duplicate large blocks of code.
14. Use meaningful variable and function names.
15. Add basic error handling.
16. Never expose API keys.
17. Do not claim a social media API integration works unless it has actually been implemented and tested.
18. Use mock/simulated publishing during development when real API credentials are unavailable.
19. Keep human approval before real publishing.
20. Validate AI-generated factual information before publication when appropriate.

---

# DEVELOPMENT PHASES

Build the project in these phases.

## PHASE 1 — Project Setup

Verify:

* Python
* venv
* Streamlit
* project structure
* requirements.txt
* .env
* .gitignore

Do not reinstall packages unnecessarily.

---

## PHASE 2 — Streamlit Dashboard

Create a professional dashboard containing:

* Sidebar
* Project name
* Campaign input
* Audience
* Tone
* Language
* Date
* Goal
* Platform selection
* Content type selection
* Generate button

Use clean UI design.

---

## PHASE 3 — AI CONNECTION

Connect the selected LLM API.

Create:

modules/content_generator.py

Implement a reusable function such as:

generate_content()

The function should receive the campaign information and platform.

Return structured output.

Handle:

* API errors
* Empty input
* Invalid responses
* Timeout
* Missing API key

---

## PHASE 4 — Platform Content Generation

Implement:

modules/email_generator.py

modules/social_generator.py

modules/blog_generator.py

modules/report_generator.py

Each module should be responsible for its own content type.

---

## PHASE 5 — Preview and Editing

The Streamlit UI should show generated content in separate sections.

Add:

* Preview
* Edit
* Regenerate
* Copy
* Approve

Do not automatically publish.

---

## PHASE 6 — Database

Use SQLite.

Store:

* campaign ID
* topic
* audience
* tone
* platform
* generated content
* created date
* scheduled date
* status
* approval status

Create:

database/database.py

Use clean CRUD functions.

---

## PHASE 7 — Content Calendar

Create a calendar/table showing:

* Date
* Platform
* Content
* Status
* Approval
* Scheduled time

Statuses:

* Draft
* Generated
* Approved
* Scheduled
* Published
* Failed

---

## PHASE 8 — Automation

Design the automation architecture.

Possible workflow:

New campaign

↓

Generate content

↓

Human approval

↓

Schedule

↓

Publish

↓

Collect analytics

Do not fake real API publishing.

If credentials are unavailable, implement a mock publishing mode.

---

## PHASE 9 — Analytics

Use Pandas and Plotly.

Display:

* Total campaigns
* Total content generated
* Emails
* Social posts
* Engagement
* Open rate
* Click rate
* Impressions

Create charts such as:

* Engagement by platform
* Campaign performance
* Email performance
* Content type distribution

---

## PHASE 10 — AI Report Generator

Use campaign analytics as input.

Generate:

* Executive summary
* Best-performing platform
* Weak-performing platform
* Key findings
* Recommendations

Never invent metrics.

If data is unavailable, clearly say that the metric is unavailable.

---

## PHASE 11 — AI Recommendations

The system should analyze campaign results and suggest:

* Better content style
* Better posting time
* Better platform
* Better audience targeting
* Better CTA
* Better hashtags
* Content improvements

Clearly label AI recommendations as recommendations, not guaranteed outcomes.

---

## PHASE 12 — Security

Implement:

* .env secrets
* .gitignore
* Input validation
* Error handling
* API failure handling
* No API keys in source code
* No sensitive data in logs

---

## PHASE 13 — Testing

Create tests for:

* Empty input
* Valid campaign
* Multiple platforms
* Invalid API key
* API failure
* Database insertion
* Database retrieval
* Content regeneration
* Approval
* Scheduling

---

## PHASE 14 — Deployment

Explain how to deploy the final Streamlit application.

Possible options:

* Streamlit Community Cloud
* AWS

Keep deployment instructions beginner-friendly.

---

# UI DESIGN

Make the dashboard look professional.

Suggested structure:

SIDEBAR:

Project Dashboard
Campaign Generator
Content Library
Content Calendar
Analytics
Reports
Settings

MAIN PAGE:

AI-Powered Multi-Platform Content Automation

Campaign Information

↓

Generate Content

↓

Generated Content

↓

Approval

↓

Analytics

Use cards, columns, tabs and Plotly charts where appropriate.

---

# IMPORTANT AI QUALITY RULES

The AI should:

* Follow the selected tone.
* Follow the target audience.
* Adapt content to each platform.
* Avoid unnecessary repetition.
* Avoid fabricated statistics.
* Avoid making unsupported factual claims.
* Clearly indicate uncertainty when information is insufficient.
* Preserve user-provided facts.
* Never invent event dates, locations, prices or statistics.
* Ask for missing critical information when required.

For reports and factual content, use supplied data as the primary source.

---

# PROJECT OUTPUT

The final project should provide:

1. AI Content Generator
2. Email Generator
3. LinkedIn Generator
4. Instagram Generator
5. Blog Generator
6. Article Generator
7. Report Generator
8. Content Editor
9. Approval System
10. Content Calendar
11. Automation Workflow
12. Analytics Dashboard
13. AI Performance Report
14. AI Recommendations
15. Database
16. Secure API configuration
17. Deployment instructions

---

# HOW YOU SHOULD WORK WITH ME

I am learning while building this project.

Therefore:

* Explain concepts in simple language.
* Don't assume advanced knowledge.
* Give commands one at a time where possible.
* Tell me what I should see after each step.
* If I send an error, diagnose it.
* Do not move ahead until the current stage works.
* When modifying a file, provide the full updated file so I can copy it safely.
* Clearly label every step.
* Keep track of the project architecture throughout the conversation.

---

# FIRST TASK

Do NOT build the whole project.

Start with:

**PHASE 1 → Verify the current project setup.**

I have already created the folders and files and already have Streamlit installed.

Tell me:

1. What should I check first?
2. Which terminal command should I run?
3. What output should I expect?
4. Then move to the next setup step only after verification.

After setup is confirmed, help me connect the AI engine and build the project incrementally.

## Output:

<img width="1600" height="773" alt="image" src="https://github.com/user-attachments/assets/5d6eab1d-d5f2-466f-b612-feb7eb88b15a" />



## Conclusion:
By applying various prompting techniques, you can generate high-quality content for a wide range of use cases, from business reports and case studies to creative works like short stories and articles. This experiment demonstrates how structured prompting can guide AI models like ChatGPT to create coherent, accurate, and engaging outputs tailored to specific needs.
