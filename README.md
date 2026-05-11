# Lead-Qualification-Agent
This is an autonomous sales agents that automatically qualifies leads based on the companies criteria, the agent immediately qualifies and triggers the next steps for the sales team.

**PURPOSE**: Companies who market themselves well soon have far too many people reaching out to them, many of which are not a good fit or "qualified" for what they sell(e.g, they are too small/not the right industry). This process of researching a new lead and deciding whether or not to take a call is known as qualification, which is what the agent automates.

**IMPACT**: This helps the sales team prioritise high potential prspects, ensuring time is spent on leads likely to convert rather than casual researches.

**USAGE/PROCESS**:

-The Lead fills and submits the form with their details

-Relevance AI company researcher scrapes the companys website to draw relevant information about them

-AI Agent looks at the information and determines based on the qualification criteria in the prompt if they are qualified or not.

-If they are, it calls the 2nd workflow which then classifies the lead into two options specifically described in the prompt(Firm/SaaS) and sends an email notification and summary of the company

-If they are not qualified, it immediately responds to the lead asking if they would like to be connected to a partner to help them instead.

**SOFTWARE**: 

n8n

**INTEGRATIONS:**

Relevance AI

Open AI GPT model

Gmail(for notification)

Form submission trigger

Secondary n8n workflow

Link to AI Agent production url: https://funmisols.app.n8n.cloud/form/00bc145c-0ea4-4a79-bcab-2353baa2f9e7
