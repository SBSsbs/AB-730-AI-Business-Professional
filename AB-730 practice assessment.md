# AB-730 Practice Questions

\--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## How to use this file

Read each explanation carefully. The goal is not only to memorize the answer, but to understand:

* Copilot capabilities across Microsoft 365 apps
* Grounding and prompt design
* Security, privacy, and responsible AI
* The difference between end-user AI tasks and admin tasks

\---

## Question 1 — Excel

You are reviewing a sales workbook in Microsoft Excel and want to prepare a management update quickly.

**Question:** Which two tasks can Microsoft 365 Copilot in Excel help you complete?

A. Generate a summary of trends and anomalies in the table
B. Rewrite the workbook's VBA macros to optimize performance
C. Build a pivot table based on the data
D. Reconfigure Excel trust center settings for all users

**Correct answer:** A, C

* **A** — Correct because Copilot in Excel is built to analyze structured data and return natural-language insights such as patterns, outliers, trends, and notable movements in the dataset.
* **C** — Correct because Copilot can help create and suggest pivot-table style analysis from tabular data so users can explore summaries faster without manually building everything from scratch.

**Why the other options are incorrect**

* **B** — Incorrect because editing or optimizing VBA code is not a core business-user Copilot-in-Excel capability in this context. The product is focused on data analysis, summarization, and productivity tasks rather than deep macro engineering.
* **D** — Incorrect because tenant-wide or application security configuration is an administrative task, not a Copilot productivity feature for spreadsheet analysis.



\---

## Question 2 — Word

You are drafting a project update in Microsoft Word for senior stakeholders.

**Question:** Which action is the BEST use of Microsoft 365 Copilot in Word?

A. Ask Copilot to summarize the draft and rewrite it in a more executive tone
B. Ask Copilot to change the printer driver settings on your computer
C. Ask Copilot to enforce corporate retention labels across SharePoint
D. Ask Copilot to repair corrupted font files in Windows

**Correct answer:** A

* **A** — Correct because Copilot in Word is designed for drafting, rewriting, summarizing, and changing tone based on audience needs. That is exactly the kind of business-writing task it supports well.

**Why the other options are incorrect**

* **B** — Incorrect because printer driver management is an operating-system task and unrelated to document authoring.
* **C** — Incorrect because retention-label enforcement is a compliance and administration function, not a Word authoring capability.
* **D** — Incorrect because repairing local fonts is a device troubleshooting task outside Copilot in Word.



\---

## Question 3 — Outlook

You open a long email thread with several participants and need to reply quickly.

**Question:** Which Microsoft 365 Copilot capability in Outlook is MOST relevant?

A. Generate a draft response grounded in the conversation context
B. Replace your organization's email security gateway rules
C. Move all mailboxes to a new Exchange region
D. Create new conditional access policies for external users

**Correct answer:** A

* **A** — Correct because Copilot in Outlook can read the thread context and propose a relevant draft reply, saving time while preserving the flow of the conversation.

**Why the other options are incorrect**

* **B** — Incorrect because mail-security gateway rules are infrastructure or security-admin tasks, not end-user Copilot features.
* **C** — Incorrect because mailbox migration is an Exchange administration activity, not a Copilot drafting scenario.
* **D** — Incorrect because conditional access is handled through identity and security administration, not through Outlook Copilot.



\---

## Question 4 — Teams

You missed part of a Microsoft Teams meeting and need the important outcomes.

**Question:** What should you use first in Microsoft 365 Copilot for Teams?

A. Recap or a meeting summary to identify decisions and action items
B. A device firmware update report
C. A tenant migration wizard
D. A custom background generator

**Correct answer:** A

* **A** — Correct because Copilot in Teams is specifically useful for post-meeting catch-up. It can summarize discussion points, decisions, owners, and next steps from meeting content.

**Why the other options are incorrect**

* **B** — Incorrect because firmware reporting is unrelated to meeting intelligence.
* **C** — Incorrect because tenant migration is a platform administration task, not a meeting productivity feature.
* **D** — Incorrect because a custom background does not help identify meeting outcomes or action items.



\---

## Question 5 — PowerPoint

You have a rough outline for a presentation and need help turning it into slides.

**Question:** Which two tasks can Copilot in PowerPoint support most directly?

A. Create a slide draft from your outline
B. Produce a summary slide from the key points
C. Change GPU driver settings for smoother animations
D. Modify the organization's approved brand assets in the admin portal

**Correct answer:** A, B

* **A** — Correct because Copilot in PowerPoint can generate slide content and propose layouts from existing text or outlines.
* **B** — Correct because summarizing the main ideas of a presentation into a concise closing or recap slide is a strong Copilot use case.

**Why the other options are incorrect**

* **C** — Incorrect because device graphics configuration is not part of presentation-generation capabilities.
* **D** — Incorrect because tenant-level brand-asset governance belongs to admins and design processes, not to Copilot's core slide-creation workflow.



\---

## Question 6 — Grounding

You ask Copilot for insights about a proposal stored in SharePoint and want the response to stay faithful to that proposal.

**Question:** What is the BEST prompt strategy?

A. Reference the specific proposal file in the prompt
B. Tell Copilot to guess likely proposal details from its general knowledge
C. Avoid mentioning any source material so the answer is more creative
D. Ask only for a stylish format without specifying the document

**Correct answer:** A

* **A** — Correct because grounding improves when Copilot is pointed to the exact source it should use. Referencing the proposal helps the model base its answer on the intended business content instead of relying mostly on general model knowledge.

**Why the other options are incorrect**

* **B** — Incorrect because asking Copilot to infer missing details increases the risk of unsupported content or hallucinations.
* **C** — Incorrect because omitting the source weakens grounding and makes the response less reliable for business use.
* **D** — Incorrect because output style matters, but it does not solve the core problem of ensuring the response is based on the proposal itself.



\---

## Question 7 — Prompt Engineering

You want Copilot to summarize a partnership proposal into three concise bullets for a kickoff meeting.

**Question:** Which two prompt elements are MOST important?

A. The specific source document to use
B. Clear instructions about the output length and style
C. A random list of stakeholder phone numbers
D. An unrelated company history from ten years ago

**Correct answer:** A, B

* **A** — Correct because Copilot needs to know what content to summarize. Naming or attaching the proposal establishes the source of truth.
* **B** — Correct because specifying 'three concise bullets' tells Copilot exactly how to shape the response for the meeting audience.

**Why the other options are incorrect**

* **C** — Incorrect because contact details do not help Copilot summarize the proposal unless the task explicitly requires them.
* **D** — Incorrect because unrelated historical background adds noise and can reduce prompt quality rather than improve it.



\---

## Question 8 — Security

A merchandiser uses Copilot suggestions based only on historical sales data and places a large order without reviewing the result or checking current market conditions.

**Question:** What does this scenario illustrate?

A. Verification
B. Overreliance on AI output
C. Prompt grounding
D. Tenant isolation

**Correct answer:** B

* **B** — Correct because the user accepted the AI recommendation without applying human judgment or validating it against current business realities. That is the classic pattern of overreliance.

**Why the other options are incorrect**

* **A** — Incorrect because verification would mean checking and validating the AI result before acting on it, which did not happen here.
* **C** — Incorrect because prompt grounding is about connecting a prompt to relevant source material, not blindly trusting an answer.
* **D** — Incorrect because tenant isolation concerns organizational data boundaries, which is not the issue in this business decision scenario.



\---

## Question 9 — Responsible AI

You receive an image that may have been generated with AI and want a trustworthy way to check its provenance.

**Question:** What should you look for first?

A. Content credentials
B. The file name
C. A long image title
D. Whether the sender used uppercase letters in the email

**Correct answer:** A

* **A** — Correct because content credentials are intended to provide provenance details and help indicate whether media was AI-generated or modified.

**Why the other options are incorrect**

* **B** — Incorrect because file names can be changed easily and do not prove origin.
* **C** — Incorrect because titles or descriptions are not a reliable provenance mechanism.
* **D** — Incorrect because sender writing style has nothing to do with verifiable media authenticity.



\---

## Question 10 — Data \& Privacy

A colleague asks how Microsoft 365 Copilot answers questions in Work scope.

**Question:** Which statement is most accurate?

A. Copilot uses all data in the tenant whether the user has permission or not
B. Copilot uses only the user's accessible organizational data plus general model knowledge
C. Copilot uses only public web results
D. Copilot uses the tenant's data to retrain the foundation model before answering

**Correct answer:** B

* **B** — Correct because Work-scope answers are grounded in organizational content the user is already allowed to access, while also benefiting from the model's general reasoning and language capabilities.

**Why the other options are incorrect**

* **A** — Incorrect because Copilot respects existing permissions and does not bypass access controls.
* **C** — Incorrect because Work scope is not limited to public web grounding; it is designed to use work data when available and authorized.
* **D** — Incorrect because tenant data is not used to retrain the underlying model in this scenario.



\---

## Question 11 — Excel

You are reviewing a sales workbook in Microsoft Excel and want to prepare a management update quickly.

**Question:** Which two tasks can Microsoft 365 Copilot in Excel help you complete?

A. Generate a summary of trends and anomalies in the table
B. Rewrite the workbook's VBA macros to optimize performance
C. Build a pivot table based on the data
D. Reconfigure Excel trust center settings for all users

**Correct answer:** A, C

* **A** — Correct because Copilot in Excel is built to analyze structured data and return natural-language insights such as patterns, outliers, trends, and notable movements in the dataset.
* **C** — Correct because Copilot can help create and suggest pivot-table style analysis from tabular data so users can explore summaries faster without manually building everything from scratch.

**Why the other options are incorrect**

* **B** — Incorrect because editing or optimizing VBA code is not a core business-user Copilot-in-Excel capability in this context. The product is focused on data analysis, summarization, and productivity tasks rather than deep macro engineering.
* **D** — Incorrect because tenant-wide or application security configuration is an administrative task, not a Copilot productivity feature for spreadsheet analysis.



\---

## Question 12 — Word

You are drafting a project update in Microsoft Word for senior stakeholders.

**Question:** Which action is the BEST use of Microsoft 365 Copilot in Word?

A. Ask Copilot to summarize the draft and rewrite it in a more executive tone
B. Ask Copilot to change the printer driver settings on your computer
C. Ask Copilot to enforce corporate retention labels across SharePoint
D. Ask Copilot to repair corrupted font files in Windows

**Correct answer:** A

* **A** — Correct because Copilot in Word is designed for drafting, rewriting, summarizing, and changing tone based on audience needs. That is exactly the kind of business-writing task it supports well.

**Why the other options are incorrect**

* **B** — Incorrect because printer driver management is an operating-system task and unrelated to document authoring.
* **C** — Incorrect because retention-label enforcement is a compliance and administration function, not a Word authoring capability.
* **D** — Incorrect because repairing local fonts is a device troubleshooting task outside Copilot in Word.



\---

## Question 13 — Outlook

You open a long email thread with several participants and need to reply quickly.

**Question:** Which Microsoft 365 Copilot capability in Outlook is MOST relevant?

A. Generate a draft response grounded in the conversation context
B. Replace your organization's email security gateway rules
C. Move all mailboxes to a new Exchange region
D. Create new conditional access policies for external users

**Correct answer:** A

* **A** — Correct because Copilot in Outlook can read the thread context and propose a relevant draft reply, saving time while preserving the flow of the conversation.

**Why the other options are incorrect**

* **B** — Incorrect because mail-security gateway rules are infrastructure or security-admin tasks, not end-user Copilot features.
* **C** — Incorrect because mailbox migration is an Exchange administration activity, not a Copilot drafting scenario.
* **D** — Incorrect because conditional access is handled through identity and security administration, not through Outlook Copilot.



\---

## Question 14 — Teams

You missed part of a Microsoft Teams meeting and need the important outcomes.

**Question:** What should you use first in Microsoft 365 Copilot for Teams?

A. Recap or a meeting summary to identify decisions and action items
B. A device firmware update report
C. A tenant migration wizard
D. A custom background generator

**Correct answer:** A

* **A** — Correct because Copilot in Teams is specifically useful for post-meeting catch-up. It can summarize discussion points, decisions, owners, and next steps from meeting content.

**Why the other options are incorrect**

* **B** — Incorrect because firmware reporting is unrelated to meeting intelligence.
* **C** — Incorrect because tenant migration is a platform administration task, not a meeting productivity feature.
* **D** — Incorrect because a custom background does not help identify meeting outcomes or action items.



\---

## Question 15 — PowerPoint

You have a rough outline for a presentation and need help turning it into slides.

**Question:** Which two tasks can Copilot in PowerPoint support most directly?

A. Create a slide draft from your outline
B. Produce a summary slide from the key points
C. Change GPU driver settings for smoother animations
D. Modify the organization's approved brand assets in the admin portal

**Correct answer:** A, B

* **A** — Correct because Copilot in PowerPoint can generate slide content and propose layouts from existing text or outlines.
* **B** — Correct because summarizing the main ideas of a presentation into a concise closing or recap slide is a strong Copilot use case.

**Why the other options are incorrect**

* **C** — Incorrect because device graphics configuration is not part of presentation-generation capabilities.
* **D** — Incorrect because tenant-level brand-asset governance belongs to admins and design processes, not to Copilot's core slide-creation workflow.



\---

## Question 16 — Grounding

You ask Copilot for insights about a proposal stored in SharePoint and want the response to stay faithful to that proposal.

**Question:** What is the BEST prompt strategy?

A. Reference the specific proposal file in the prompt
B. Tell Copilot to guess likely proposal details from its general knowledge
C. Avoid mentioning any source material so the answer is more creative
D. Ask only for a stylish format without specifying the document

**Correct answer:** A

* **A** — Correct because grounding improves when Copilot is pointed to the exact source it should use. Referencing the proposal helps the model base its answer on the intended business content instead of relying mostly on general model knowledge.

**Why the other options are incorrect**

* **B** — Incorrect because asking Copilot to infer missing details increases the risk of unsupported content or hallucinations.
* **C** — Incorrect because omitting the source weakens grounding and makes the response less reliable for business use.
* **D** — Incorrect because output style matters, but it does not solve the core problem of ensuring the response is based on the proposal itself.



\---

## Question 17 — Prompt Engineering

You want Copilot to summarize a partnership proposal into three concise bullets for a kickoff meeting.

**Question:** Which two prompt elements are MOST important?

A. The specific source document to use
B. Clear instructions about the output length and style
C. A random list of stakeholder phone numbers
D. An unrelated company history from ten years ago

**Correct answer:** A, B

* **A** — Correct because Copilot needs to know what content to summarize. Naming or attaching the proposal establishes the source of truth.
* **B** — Correct because specifying 'three concise bullets' tells Copilot exactly how to shape the response for the meeting audience.

**Why the other options are incorrect**

* **C** — Incorrect because contact details do not help Copilot summarize the proposal unless the task explicitly requires them.
* **D** — Incorrect because unrelated historical background adds noise and can reduce prompt quality rather than improve it.



\---

## Question 18 — Security

A merchandiser uses Copilot suggestions based only on historical sales data and places a large order without reviewing the result or checking current market conditions.

**Question:** What does this scenario illustrate?

A. Verification
B. Overreliance on AI output
C. Prompt grounding
D. Tenant isolation

**Correct answer:** B

* **B** — Correct because the user accepted the AI recommendation without applying human judgment or validating it against current business realities. That is the classic pattern of overreliance.

**Why the other options are incorrect**

* **A** — Incorrect because verification would mean checking and validating the AI result before acting on it, which did not happen here.
* **C** — Incorrect because prompt grounding is about connecting a prompt to relevant source material, not blindly trusting an answer.
* **D** — Incorrect because tenant isolation concerns organizational data boundaries, which is not the issue in this business decision scenario.



\---

## Question 19 — Responsible AI

You receive an image that may have been generated with AI and want a trustworthy way to check its provenance.

**Question:** What should you look for first?

A. Content credentials
B. The file name
C. A long image title
D. Whether the sender used uppercase letters in the email

**Correct answer:** A

* **A** — Correct because content credentials are intended to provide provenance details and help indicate whether media was AI-generated or modified.

**Why the other options are incorrect**

* **B** — Incorrect because file names can be changed easily and do not prove origin.
* **C** — Incorrect because titles or descriptions are not a reliable provenance mechanism.
* **D** — Incorrect because sender writing style has nothing to do with verifiable media authenticity.



\---

## Question 20 — Data \& Privacy

A colleague asks how Microsoft 365 Copilot answers questions in Work scope.

**Question:** Which statement is most accurate?

A. Copilot uses all data in the tenant whether the user has permission or not
B. Copilot uses only the user's accessible organizational data plus general model knowledge
C. Copilot uses only public web results
D. Copilot uses the tenant's data to retrain the foundation model before answering

**Correct answer:** B

* **B** — Correct because Work-scope answers are grounded in organizational content the user is already allowed to access, while also benefiting from the model's general reasoning and language capabilities.

**Why the other options are incorrect**

* **A** — Incorrect because Copilot respects existing permissions and does not bypass access controls.
* **C** — Incorrect because Work scope is not limited to public web grounding; it is designed to use work data when available and authorized.
* **D** — Incorrect because tenant data is not used to retrain the underlying model in this scenario.



\---

## Question 21 — Excel

You are reviewing a sales workbook in Microsoft Excel and want to prepare a management update quickly.

**Question:** Which two tasks can Microsoft 365 Copilot in Excel help you complete?

A. Generate a summary of trends and anomalies in the table
B. Rewrite the workbook's VBA macros to optimize performance
C. Build a pivot table based on the data
D. Reconfigure Excel trust center settings for all users

**Correct answer:** A, C

* **A** — Correct because Copilot in Excel is built to analyze structured data and return natural-language insights such as patterns, outliers, trends, and notable movements in the dataset.
* **C** — Correct because Copilot can help create and suggest pivot-table style analysis from tabular data so users can explore summaries faster without manually building everything from scratch.

**Why the other options are incorrect**

* **B** — Incorrect because editing or optimizing VBA code is not a core business-user Copilot-in-Excel capability in this context. The product is focused on data analysis, summarization, and productivity tasks rather than deep macro engineering.
* **D** — Incorrect because tenant-wide or application security configuration is an administrative task, not a Copilot productivity feature for spreadsheet analysis.



\---

## Question 22 — Word

You are drafting a project update in Microsoft Word for senior stakeholders.

**Question:** Which action is the BEST use of Microsoft 365 Copilot in Word?

A. Ask Copilot to summarize the draft and rewrite it in a more executive tone
B. Ask Copilot to change the printer driver settings on your computer
C. Ask Copilot to enforce corporate retention labels across SharePoint
D. Ask Copilot to repair corrupted font files in Windows

**Correct answer:** A

* **A** — Correct because Copilot in Word is designed for drafting, rewriting, summarizing, and changing tone based on audience needs. That is exactly the kind of business-writing task it supports well.

**Why the other options are incorrect**

* **B** — Incorrect because printer driver management is an operating-system task and unrelated to document authoring.
* **C** — Incorrect because retention-label enforcement is a compliance and administration function, not a Word authoring capability.
* **D** — Incorrect because repairing local fonts is a device troubleshooting task outside Copilot in Word.



\---

## Question 23 — Outlook

You open a long email thread with several participants and need to reply quickly.

**Question:** Which Microsoft 365 Copilot capability in Outlook is MOST relevant?

A. Generate a draft response grounded in the conversation context
B. Replace your organization's email security gateway rules
C. Move all mailboxes to a new Exchange region
D. Create new conditional access policies for external users

**Correct answer:** A

* **A** — Correct because Copilot in Outlook can read the thread context and propose a relevant draft reply, saving time while preserving the flow of the conversation.

**Why the other options are incorrect**

* **B** — Incorrect because mail-security gateway rules are infrastructure or security-admin tasks, not end-user Copilot features.
* **C** — Incorrect because mailbox migration is an Exchange administration activity, not a Copilot drafting scenario.
* **D** — Incorrect because conditional access is handled through identity and security administration, not through Outlook Copilot.



\---

## Question 24 — Teams

You missed part of a Microsoft Teams meeting and need the important outcomes.

**Question:** What should you use first in Microsoft 365 Copilot for Teams?

A. Recap or a meeting summary to identify decisions and action items
B. A device firmware update report
C. A tenant migration wizard
D. A custom background generator

**Correct answer:** A

* **A** — Correct because Copilot in Teams is specifically useful for post-meeting catch-up. It can summarize discussion points, decisions, owners, and next steps from meeting content.

**Why the other options are incorrect**

* **B** — Incorrect because firmware reporting is unrelated to meeting intelligence.
* **C** — Incorrect because tenant migration is a platform administration task, not a meeting productivity feature.
* **D** — Incorrect because a custom background does not help identify meeting outcomes or action items.



\---

## Question 25 — PowerPoint

You have a rough outline for a presentation and need help turning it into slides.

**Question:** Which two tasks can Copilot in PowerPoint support most directly?

A. Create a slide draft from your outline
B. Produce a summary slide from the key points
C. Change GPU driver settings for smoother animations
D. Modify the organization's approved brand assets in the admin portal

**Correct answer:** A, B

* **A** — Correct because Copilot in PowerPoint can generate slide content and propose layouts from existing text or outlines.
* **B** — Correct because summarizing the main ideas of a presentation into a concise closing or recap slide is a strong Copilot use case.

**Why the other options are incorrect**

* **C** — Incorrect because device graphics configuration is not part of presentation-generation capabilities.
* **D** — Incorrect because tenant-level brand-asset governance belongs to admins and design processes, not to Copilot's core slide-creation workflow.



\---

## Question 26 — Grounding

You ask Copilot for insights about a proposal stored in SharePoint and want the response to stay faithful to that proposal.

**Question:** What is the BEST prompt strategy?

A. Reference the specific proposal file in the prompt
B. Tell Copilot to guess likely proposal details from its general knowledge
C. Avoid mentioning any source material so the answer is more creative
D. Ask only for a stylish format without specifying the document

**Correct answer:** A

* **A** — Correct because grounding improves when Copilot is pointed to the exact source it should use. Referencing the proposal helps the model base its answer on the intended business content instead of relying mostly on general model knowledge.

**Why the other options are incorrect**

* **B** — Incorrect because asking Copilot to infer missing details increases the risk of unsupported content or hallucinations.
* **C** — Incorrect because omitting the source weakens grounding and makes the response less reliable for business use.
* **D** — Incorrect because output style matters, but it does not solve the core problem of ensuring the response is based on the proposal itself.



\---

## Question 27 — Prompt Engineering

You want Copilot to summarize a partnership proposal into three concise bullets for a kickoff meeting.

**Question:** Which two prompt elements are MOST important?

A. The specific source document to use
B. Clear instructions about the output length and style
C. A random list of stakeholder phone numbers
D. An unrelated company history from ten years ago

**Correct answer:** A, B

* **A** — Correct because Copilot needs to know what content to summarize. Naming or attaching the proposal establishes the source of truth.
* **B** — Correct because specifying 'three concise bullets' tells Copilot exactly how to shape the response for the meeting audience.

**Why the other options are incorrect**

* **C** — Incorrect because contact details do not help Copilot summarize the proposal unless the task explicitly requires them.
* **D** — Incorrect because unrelated historical background adds noise and can reduce prompt quality rather than improve it.



\---

## Question 28 — Security

A merchandiser uses Copilot suggestions based only on historical sales data and places a large order without reviewing the result or checking current market conditions.

**Question:** What does this scenario illustrate?

A. Verification
B. Overreliance on AI output
C. Prompt grounding
D. Tenant isolation

**Correct answer:** B

* **B** — Correct because the user accepted the AI recommendation without applying human judgment or validating it against current business realities. That is the classic pattern of overreliance.

**Why the other options are incorrect**

* **A** — Incorrect because verification would mean checking and validating the AI result before acting on it, which did not happen here.
* **C** — Incorrect because prompt grounding is about connecting a prompt to relevant source material, not blindly trusting an answer.
* **D** — Incorrect because tenant isolation concerns organizational data boundaries, which is not the issue in this business decision scenario.



\---

## Question 29 — Responsible AI

You receive an image that may have been generated with AI and want a trustworthy way to check its provenance.

**Question:** What should you look for first?

A. Content credentials
B. The file name
C. A long image title
D. Whether the sender used uppercase letters in the email

**Correct answer:** A

* **A** — Correct because content credentials are intended to provide provenance details and help indicate whether media was AI-generated or modified.

**Why the other options are incorrect**

* **B** — Incorrect because file names can be changed easily and do not prove origin.
* **C** — Incorrect because titles or descriptions are not a reliable provenance mechanism.
* **D** — Incorrect because sender writing style has nothing to do with verifiable media authenticity.



\---

## Question 30 — Data \& Privacy

A colleague asks how Microsoft 365 Copilot answers questions in Work scope.

**Question:** Which statement is most accurate?

A. Copilot uses all data in the tenant whether the user has permission or not
B. Copilot uses only the user's accessible organizational data plus general model knowledge
C. Copilot uses only public web results
D. Copilot uses the tenant's data to retrain the foundation model before answering

**Correct answer:** B

* **B** — Correct because Work-scope answers are grounded in organizational content the user is already allowed to access, while also benefiting from the model's general reasoning and language capabilities.

**Why the other options are incorrect**

* **A** — Incorrect because Copilot respects existing permissions and does not bypass access controls.
* **C** — Incorrect because Work scope is not limited to public web grounding; it is designed to use work data when available and authorized.
* **D** — Incorrect because tenant data is not used to retrain the underlying model in this scenario.



\---

## Question 31 — Excel

You are reviewing a sales workbook in Microsoft Excel and want to prepare a management update quickly.

**Question:** Which two tasks can Microsoft 365 Copilot in Excel help you complete?

A. Generate a summary of trends and anomalies in the table
B. Rewrite the workbook's VBA macros to optimize performance
C. Build a pivot table based on the data
D. Reconfigure Excel trust center settings for all users

**Correct answer:** A, C

* **A** — Correct because Copilot in Excel is built to analyze structured data and return natural-language insights such as patterns, outliers, trends, and notable movements in the dataset.
* **C** — Correct because Copilot can help create and suggest pivot-table style analysis from tabular data so users can explore summaries faster without manually building everything from scratch.

**Why the other options are incorrect**

* **B** — Incorrect because editing or optimizing VBA code is not a core business-user Copilot-in-Excel capability in this context. The product is focused on data analysis, summarization, and productivity tasks rather than deep macro engineering.
* **D** — Incorrect because tenant-wide or application security configuration is an administrative task, not a Copilot productivity feature for spreadsheet analysis.



\---

## Question 32 — Word

You are drafting a project update in Microsoft Word for senior stakeholders.

**Question:** Which action is the BEST use of Microsoft 365 Copilot in Word?

A. Ask Copilot to summarize the draft and rewrite it in a more executive tone
B. Ask Copilot to change the printer driver settings on your computer
C. Ask Copilot to enforce corporate retention labels across SharePoint
D. Ask Copilot to repair corrupted font files in Windows

**Correct answer:** A

* **A** — Correct because Copilot in Word is designed for drafting, rewriting, summarizing, and changing tone based on audience needs. That is exactly the kind of business-writing task it supports well.

**Why the other options are incorrect**

* **B** — Incorrect because printer driver management is an operating-system task and unrelated to document authoring.
* **C** — Incorrect because retention-label enforcement is a compliance and administration function, not a Word authoring capability.
* **D** — Incorrect because repairing local fonts is a device troubleshooting task outside Copilot in Word.



\---

## Question 33 — Outlook

You open a long email thread with several participants and need to reply quickly.

**Question:** Which Microsoft 365 Copilot capability in Outlook is MOST relevant?

A. Generate a draft response grounded in the conversation context
B. Replace your organization's email security gateway rules
C. Move all mailboxes to a new Exchange region
D. Create new conditional access policies for external users

**Correct answer:** A

* **A** — Correct because Copilot in Outlook can read the thread context and propose a relevant draft reply, saving time while preserving the flow of the conversation.

**Why the other options are incorrect**

* **B** — Incorrect because mail-security gateway rules are infrastructure or security-admin tasks, not end-user Copilot features.
* **C** — Incorrect because mailbox migration is an Exchange administration activity, not a Copilot drafting scenario.
* **D** — Incorrect because conditional access is handled through identity and security administration, not through Outlook Copilot.



\---

## Question 34 — Teams

You missed part of a Microsoft Teams meeting and need the important outcomes.

**Question:** What should you use first in Microsoft 365 Copilot for Teams?

A. Recap or a meeting summary to identify decisions and action items
B. A device firmware update report
C. A tenant migration wizard
D. A custom background generator

**Correct answer:** A

* **A** — Correct because Copilot in Teams is specifically useful for post-meeting catch-up. It can summarize discussion points, decisions, owners, and next steps from meeting content.

**Why the other options are incorrect**

* **B** — Incorrect because firmware reporting is unrelated to meeting intelligence.
* **C** — Incorrect because tenant migration is a platform administration task, not a meeting productivity feature.
* **D** — Incorrect because a custom background does not help identify meeting outcomes or action items.



\---

## Question 35 — PowerPoint

You have a rough outline for a presentation and need help turning it into slides.

**Question:** Which two tasks can Copilot in PowerPoint support most directly?

A. Create a slide draft from your outline
B. Produce a summary slide from the key points
C. Change GPU driver settings for smoother animations
D. Modify the organization's approved brand assets in the admin portal

**Correct answer:** A, B

* **A** — Correct because Copilot in PowerPoint can generate slide content and propose layouts from existing text or outlines.
* **B** — Correct because summarizing the main ideas of a presentation into a concise closing or recap slide is a strong Copilot use case.

**Why the other options are incorrect**

* **C** — Incorrect because device graphics configuration is not part of presentation-generation capabilities.
* **D** — Incorrect because tenant-level brand-asset governance belongs to admins and design processes, not to Copilot's core slide-creation workflow.



\---

## Question 36 — Grounding

You ask Copilot for insights about a proposal stored in SharePoint and want the response to stay faithful to that proposal.

**Question:** What is the BEST prompt strategy?

A. Reference the specific proposal file in the prompt
B. Tell Copilot to guess likely proposal details from its general knowledge
C. Avoid mentioning any source material so the answer is more creative
D. Ask only for a stylish format without specifying the document

**Correct answer:** A

* **A** — Correct because grounding improves when Copilot is pointed to the exact source it should use. Referencing the proposal helps the model base its answer on the intended business content instead of relying mostly on general model knowledge.

**Why the other options are incorrect**

* **B** — Incorrect because asking Copilot to infer missing details increases the risk of unsupported content or hallucinations.
* **C** — Incorrect because omitting the source weakens grounding and makes the response less reliable for business use.
* **D** — Incorrect because output style matters, but it does not solve the core problem of ensuring the response is based on the proposal itself.



\---

## Question 37 — Prompt Engineering

You want Copilot to summarize a partnership proposal into three concise bullets for a kickoff meeting.

**Question:** Which two prompt elements are MOST important?

A. The specific source document to use
B. Clear instructions about the output length and style
C. A random list of stakeholder phone numbers
D. An unrelated company history from ten years ago

**Correct answer:** A, B

* **A** — Correct because Copilot needs to know what content to summarize. Naming or attaching the proposal establishes the source of truth.
* **B** — Correct because specifying 'three concise bullets' tells Copilot exactly how to shape the response for the meeting audience.

**Why the other options are incorrect**

* **C** — Incorrect because contact details do not help Copilot summarize the proposal unless the task explicitly requires them.
* **D** — Incorrect because unrelated historical background adds noise and can reduce prompt quality rather than improve it.



\---

## Question 38 — Security

A merchandiser uses Copilot suggestions based only on historical sales data and places a large order without reviewing the result or checking current market conditions.

**Question:** What does this scenario illustrate?

A. Verification
B. Overreliance on AI output
C. Prompt grounding
D. Tenant isolation

**Correct answer:** B

* **B** — Correct because the user accepted the AI recommendation without applying human judgment or validating it against current business realities. That is the classic pattern of overreliance.

**Why the other options are incorrect**

* **A** — Incorrect because verification would mean checking and validating the AI result before acting on it, which did not happen here.
* **C** — Incorrect because prompt grounding is about connecting a prompt to relevant source material, not blindly trusting an answer.
* **D** — Incorrect because tenant isolation concerns organizational data boundaries, which is not the issue in this business decision scenario.



\---

## Question 39 — Responsible AI

You receive an image that may have been generated with AI and want a trustworthy way to check its provenance.

**Question:** What should you look for first?

A. Content credentials
B. The file name
C. A long image title
D. Whether the sender used uppercase letters in the email

**Correct answer:** A

* **A** — Correct because content credentials are intended to provide provenance details and help indicate whether media was AI-generated or modified.

**Why the other options are incorrect**

* **B** — Incorrect because file names can be changed easily and do not prove origin.
* **C** — Incorrect because titles or descriptions are not a reliable provenance mechanism.
* **D** — Incorrect because sender writing style has nothing to do with verifiable media authenticity.



\---

## Question 40 — Data \& Privacy

A colleague asks how Microsoft 365 Copilot answers questions in Work scope.

**Question:** Which statement is most accurate?

A. Copilot uses all data in the tenant whether the user has permission or not
B. Copilot uses only the user's accessible organizational data plus general model knowledge
C. Copilot uses only public web results
D. Copilot uses the tenant's data to retrain the foundation model before answering

**Correct answer:** B

* **B** — Correct because Work-scope answers are grounded in organizational content the user is already allowed to access, while also benefiting from the model's general reasoning and language capabilities.

**Why the other options are incorrect**

* **A** — Incorrect because Copilot respects existing permissions and does not bypass access controls.
* **C** — Incorrect because Work scope is not limited to public web grounding; it is designed to use work data when available and authorized.
* **D** — Incorrect because tenant data is not used to retrain the underlying model in this scenario.



\---

## Question 41 — Excel

You are reviewing a sales workbook in Microsoft Excel and want to prepare a management update quickly.

**Question:** Which two tasks can Microsoft 365 Copilot in Excel help you complete?

A. Generate a summary of trends and anomalies in the table
B. Rewrite the workbook's VBA macros to optimize performance
C. Build a pivot table based on the data
D. Reconfigure Excel trust center settings for all users

**Correct answer:** A, C

* **A** — Correct because Copilot in Excel is built to analyze structured data and return natural-language insights such as patterns, outliers, trends, and notable movements in the dataset.
* **C** — Correct because Copilot can help create and suggest pivot-table style analysis from tabular data so users can explore summaries faster without manually building everything from scratch.

**Why the other options are incorrect**

* **B** — Incorrect because editing or optimizing VBA code is not a core business-user Copilot-in-Excel capability in this context. The product is focused on data analysis, summarization, and productivity tasks rather than deep macro engineering.
* **D** — Incorrect because tenant-wide or application security configuration is an administrative task, not a Copilot productivity feature for spreadsheet analysis.



\---

## Question 42 — Word

You are drafting a project update in Microsoft Word for senior stakeholders.

**Question:** Which action is the BEST use of Microsoft 365 Copilot in Word?

A. Ask Copilot to summarize the draft and rewrite it in a more executive tone
B. Ask Copilot to change the printer driver settings on your computer
C. Ask Copilot to enforce corporate retention labels across SharePoint
D. Ask Copilot to repair corrupted font files in Windows

**Correct answer:** A

* **A** — Correct because Copilot in Word is designed for drafting, rewriting, summarizing, and changing tone based on audience needs. That is exactly the kind of business-writing task it supports well.

**Why the other options are incorrect**

* **B** — Incorrect because printer driver management is an operating-system task and unrelated to document authoring.
* **C** — Incorrect because retention-label enforcement is a compliance and administration function, not a Word authoring capability.
* **D** — Incorrect because repairing local fonts is a device troubleshooting task outside Copilot in Word.



\---

## Question 43 — Outlook

You open a long email thread with several participants and need to reply quickly.

**Question:** Which Microsoft 365 Copilot capability in Outlook is MOST relevant?

A. Generate a draft response grounded in the conversation context
B. Replace your organization's email security gateway rules
C. Move all mailboxes to a new Exchange region
D. Create new conditional access policies for external users

**Correct answer:** A

* **A** — Correct because Copilot in Outlook can read the thread context and propose a relevant draft reply, saving time while preserving the flow of the conversation.

**Why the other options are incorrect**

* **B** — Incorrect because mail-security gateway rules are infrastructure or security-admin tasks, not end-user Copilot features.
* **C** — Incorrect because mailbox migration is an Exchange administration activity, not a Copilot drafting scenario.
* **D** — Incorrect because conditional access is handled through identity and security administration, not through Outlook Copilot.



\---

## Question 44 — Teams

You missed part of a Microsoft Teams meeting and need the important outcomes.

**Question:** What should you use first in Microsoft 365 Copilot for Teams?

A. Recap or a meeting summary to identify decisions and action items
B. A device firmware update report
C. A tenant migration wizard
D. A custom background generator

**Correct answer:** A

* **A** — Correct because Copilot in Teams is specifically useful for post-meeting catch-up. It can summarize discussion points, decisions, owners, and next steps from meeting content.

**Why the other options are incorrect**

* **B** — Incorrect because firmware reporting is unrelated to meeting intelligence.
* **C** — Incorrect because tenant migration is a platform administration task, not a meeting productivity feature.
* **D** — Incorrect because a custom background does not help identify meeting outcomes or action items.



\---

## Question 45 — PowerPoint

You have a rough outline for a presentation and need help turning it into slides.

**Question:** Which two tasks can Copilot in PowerPoint support most directly?

A. Create a slide draft from your outline
B. Produce a summary slide from the key points
C. Change GPU driver settings for smoother animations
D. Modify the organization's approved brand assets in the admin portal

**Correct answer:** A, B

* **A** — Correct because Copilot in PowerPoint can generate slide content and propose layouts from existing text or outlines.
* **B** — Correct because summarizing the main ideas of a presentation into a concise closing or recap slide is a strong Copilot use case.

**Why the other options are incorrect**

* **C** — Incorrect because device graphics configuration is not part of presentation-generation capabilities.
* **D** — Incorrect because tenant-level brand-asset governance belongs to admins and design processes, not to Copilot's core slide-creation workflow.



\---

## Question 46 — Grounding

You ask Copilot for insights about a proposal stored in SharePoint and want the response to stay faithful to that proposal.

**Question:** What is the BEST prompt strategy?

A. Reference the specific proposal file in the prompt
B. Tell Copilot to guess likely proposal details from its general knowledge
C. Avoid mentioning any source material so the answer is more creative
D. Ask only for a stylish format without specifying the document

**Correct answer:** A

* **A** — Correct because grounding improves when Copilot is pointed to the exact source it should use. Referencing the proposal helps the model base its answer on the intended business content instead of relying mostly on general model knowledge.

**Why the other options are incorrect**

* **B** — Incorrect because asking Copilot to infer missing details increases the risk of unsupported content or hallucinations.
* **C** — Incorrect because omitting the source weakens grounding and makes the response less reliable for business use.
* **D** — Incorrect because output style matters, but it does not solve the core problem of ensuring the response is based on the proposal itself.



\---

## Question 47 — Prompt Engineering

You want Copilot to summarize a partnership proposal into three concise bullets for a kickoff meeting.

**Question:** Which two prompt elements are MOST important?

A. The specific source document to use
B. Clear instructions about the output length and style
C. A random list of stakeholder phone numbers
D. An unrelated company history from ten years ago

**Correct answer:** A, B

* **A** — Correct because Copilot needs to know what content to summarize. Naming or attaching the proposal establishes the source of truth.
* **B** — Correct because specifying 'three concise bullets' tells Copilot exactly how to shape the response for the meeting audience.

**Why the other options are incorrect**

* **C** — Incorrect because contact details do not help Copilot summarize the proposal unless the task explicitly requires them.
* **D** — Incorrect because unrelated historical background adds noise and can reduce prompt quality rather than improve it.



\---

## Question 48 — Security

A merchandiser uses Copilot suggestions based only on historical sales data and places a large order without reviewing the result or checking current market conditions.

**Question:** What does this scenario illustrate?

A. Verification
B. Overreliance on AI output
C. Prompt grounding
D. Tenant isolation

**Correct answer:** B

* **B** — Correct because the user accepted the AI recommendation without applying human judgment or validating it against current business realities. That is the classic pattern of overreliance.

**Why the other options are incorrect**

* **A** — Incorrect because verification would mean checking and validating the AI result before acting on it, which did not happen here.
* **C** — Incorrect because prompt grounding is about connecting a prompt to relevant source material, not blindly trusting an answer.
* **D** — Incorrect because tenant isolation concerns organizational data boundaries, which is not the issue in this business decision scenario.



\---

## Question 49 — Responsible AI

You receive an image that may have been generated with AI and want a trustworthy way to check its provenance.

**Question:** What should you look for first?

A. Content credentials
B. The file name
C. A long image title
D. Whether the sender used uppercase letters in the email

**Correct answer:** A

* **A** — Correct because content credentials are intended to provide provenance details and help indicate whether media was AI-generated or modified.

**Why the other options are incorrect**

* **B** — Incorrect because file names can be changed easily and do not prove origin.
* **C** — Incorrect because titles or descriptions are not a reliable provenance mechanism.
* **D** — Incorrect because sender writing style has nothing to do with verifiable media authenticity.



\---

## Question 50 — Data \& Privacy

A colleague asks how Microsoft 365 Copilot answers questions in Work scope.

**Question:** Which statement is most accurate?

A. Copilot uses all data in the tenant whether the user has permission or not
B. Copilot uses only the user's accessible organizational data plus general model knowledge
C. Copilot uses only public web results
D. Copilot uses the tenant's data to retrain the foundation model before answering

**Correct answer:** B

* **B** — Correct because Work-scope answers are grounded in organizational content the user is already allowed to access, while also benefiting from the model's general reasoning and language capabilities.

**Why the other options are incorrect**

* **A** — Incorrect because Copilot respects existing permissions and does not bypass access controls.
* **C** — Incorrect because Work scope is not limited to public web grounding; it is designed to use work data when available and authorized.
* **D** — Incorrect because tenant data is not used to retrain the underlying model in this scenario.



\---

## Question 51 — Excel

You are reviewing a sales workbook in Microsoft Excel and want to prepare a management update quickly.

**Question:** Which two tasks can Microsoft 365 Copilot in Excel help you complete?

A. Generate a summary of trends and anomalies in the table
B. Rewrite the workbook's VBA macros to optimize performance
C. Build a pivot table based on the data
D. Reconfigure Excel trust center settings for all users

**Correct answer:** A, C

* **A** — Correct because Copilot in Excel is built to analyze structured data and return natural-language insights such as patterns, outliers, trends, and notable movements in the dataset.
* **C** — Correct because Copilot can help create and suggest pivot-table style analysis from tabular data so users can explore summaries faster without manually building everything from scratch.

**Why the other options are incorrect**

* **B** — Incorrect because editing or optimizing VBA code is not a core business-user Copilot-in-Excel capability in this context. The product is focused on data analysis, summarization, and productivity tasks rather than deep macro engineering.
* **D** — Incorrect because tenant-wide or application security configuration is an administrative task, not a Copilot productivity feature for spreadsheet analysis.



\---

## Question 52 — Word

You are drafting a project update in Microsoft Word for senior stakeholders.

**Question:** Which action is the BEST use of Microsoft 365 Copilot in Word?

A. Ask Copilot to summarize the draft and rewrite it in a more executive tone
B. Ask Copilot to change the printer driver settings on your computer
C. Ask Copilot to enforce corporate retention labels across SharePoint
D. Ask Copilot to repair corrupted font files in Windows

**Correct answer:** A

* **A** — Correct because Copilot in Word is designed for drafting, rewriting, summarizing, and changing tone based on audience needs. That is exactly the kind of business-writing task it supports well.

**Why the other options are incorrect**

* **B** — Incorrect because printer driver management is an operating-system task and unrelated to document authoring.
* **C** — Incorrect because retention-label enforcement is a compliance and administration function, not a Word authoring capability.
* **D** — Incorrect because repairing local fonts is a device troubleshooting task outside Copilot in Word.



\---

## Question 53 — Outlook

You open a long email thread with several participants and need to reply quickly.

**Question:** Which Microsoft 365 Copilot capability in Outlook is MOST relevant?

A. Generate a draft response grounded in the conversation context
B. Replace your organization's email security gateway rules
C. Move all mailboxes to a new Exchange region
D. Create new conditional access policies for external users

**Correct answer:** A

* **A** — Correct because Copilot in Outlook can read the thread context and propose a relevant draft reply, saving time while preserving the flow of the conversation.

**Why the other options are incorrect**

* **B** — Incorrect because mail-security gateway rules are infrastructure or security-admin tasks, not end-user Copilot features.
* **C** — Incorrect because mailbox migration is an Exchange administration activity, not a Copilot drafting scenario.
* **D** — Incorrect because conditional access is handled through identity and security administration, not through Outlook Copilot.



\---

## Question 54 — Teams

You missed part of a Microsoft Teams meeting and need the important outcomes.

**Question:** What should you use first in Microsoft 365 Copilot for Teams?

A. Recap or a meeting summary to identify decisions and action items
B. A device firmware update report
C. A tenant migration wizard
D. A custom background generator

**Correct answer:** A

* **A** — Correct because Copilot in Teams is specifically useful for post-meeting catch-up. It can summarize discussion points, decisions, owners, and next steps from meeting content.

**Why the other options are incorrect**

* **B** — Incorrect because firmware reporting is unrelated to meeting intelligence.
* **C** — Incorrect because tenant migration is a platform administration task, not a meeting productivity feature.
* **D** — Incorrect because a custom background does not help identify meeting outcomes or action items.



\---

## Question 55 — PowerPoint

You have a rough outline for a presentation and need help turning it into slides.

**Question:** Which two tasks can Copilot in PowerPoint support most directly?

A. Create a slide draft from your outline
B. Produce a summary slide from the key points
C. Change GPU driver settings for smoother animations
D. Modify the organization's approved brand assets in the admin portal

**Correct answer:** A, B

* **A** — Correct because Copilot in PowerPoint can generate slide content and propose layouts from existing text or outlines.
* **B** — Correct because summarizing the main ideas of a presentation into a concise closing or recap slide is a strong Copilot use case.

**Why the other options are incorrect**

* **C** — Incorrect because device graphics configuration is not part of presentation-generation capabilities.
* **D** — Incorrect because tenant-level brand-asset governance belongs to admins and design processes, not to Copilot's core slide-creation workflow.



\---

## Question 56 — Grounding

You ask Copilot for insights about a proposal stored in SharePoint and want the response to stay faithful to that proposal.

**Question:** What is the BEST prompt strategy?

A. Reference the specific proposal file in the prompt
B. Tell Copilot to guess likely proposal details from its general knowledge
C. Avoid mentioning any source material so the answer is more creative
D. Ask only for a stylish format without specifying the document

**Correct answer:** A

* **A** — Correct because grounding improves when Copilot is pointed to the exact source it should use. Referencing the proposal helps the model base its answer on the intended business content instead of relying mostly on general model knowledge.

**Why the other options are incorrect**

* **B** — Incorrect because asking Copilot to infer missing details increases the risk of unsupported content or hallucinations.
* **C** — Incorrect because omitting the source weakens grounding and makes the response less reliable for business use.
* **D** — Incorrect because output style matters, but it does not solve the core problem of ensuring the response is based on the proposal itself.



\---

## Question 57 — Prompt Engineering

You want Copilot to summarize a partnership proposal into three concise bullets for a kickoff meeting.

**Question:** Which two prompt elements are MOST important?

A. The specific source document to use
B. Clear instructions about the output length and style
C. A random list of stakeholder phone numbers
D. An unrelated company history from ten years ago

**Correct answer:** A, B

* **A** — Correct because Copilot needs to know what content to summarize. Naming or attaching the proposal establishes the source of truth.
* **B** — Correct because specifying 'three concise bullets' tells Copilot exactly how to shape the response for the meeting audience.

**Why the other options are incorrect**

* **C** — Incorrect because contact details do not help Copilot summarize the proposal unless the task explicitly requires them.
* **D** — Incorrect because unrelated historical background adds noise and can reduce prompt quality rather than improve it.



\---

## Question 58 — Security

A merchandiser uses Copilot suggestions based only on historical sales data and places a large order without reviewing the result or checking current market conditions.

**Question:** What does this scenario illustrate?

A. Verification
B. Overreliance on AI output
C. Prompt grounding
D. Tenant isolation

**Correct answer:** B

* **B** — Correct because the user accepted the AI recommendation without applying human judgment or validating it against current business realities. That is the classic pattern of overreliance.

**Why the other options are incorrect**

* **A** — Incorrect because verification would mean checking and validating the AI result before acting on it, which did not happen here.
* **C** — Incorrect because prompt grounding is about connecting a prompt to relevant source material, not blindly trusting an answer.
* **D** — Incorrect because tenant isolation concerns organizational data boundaries, which is not the issue in this business decision scenario.



\---

## Question 59 — Responsible AI

You receive an image that may have been generated with AI and want a trustworthy way to check its provenance.

**Question:** What should you look for first?

A. Content credentials
B. The file name
C. A long image title
D. Whether the sender used uppercase letters in the email

**Correct answer:** A

* **A** — Correct because content credentials are intended to provide provenance details and help indicate whether media was AI-generated or modified.

**Why the other options are incorrect**

* **B** — Incorrect because file names can be changed easily and do not prove origin.
* **C** — Incorrect because titles or descriptions are not a reliable provenance mechanism.
* **D** — Incorrect because sender writing style has nothing to do with verifiable media authenticity.



\---

## Question 60 — Data \& Privacy

A colleague asks how Microsoft 365 Copilot answers questions in Work scope.

**Question:** Which statement is most accurate?

A. Copilot uses all data in the tenant whether the user has permission or not
B. Copilot uses only the user's accessible organizational data plus general model knowledge
C. Copilot uses only public web results
D. Copilot uses the tenant's data to retrain the foundation model before answering

**Correct answer:** B

* **B** — Correct because Work-scope answers are grounded in organizational content the user is already allowed to access, while also benefiting from the model's general reasoning and language capabilities.

**Why the other options are incorrect**

* **A** — Incorrect because Copilot respects existing permissions and does not bypass access controls.
* **C** — Incorrect because Work scope is not limited to public web grounding; it is designed to use work data when available and authorized.
* **D** — Incorrect because tenant data is not used to retrain the underlying model in this scenario.



\---

## Question 61 — Excel

You are reviewing a sales workbook in Microsoft Excel and want to prepare a management update quickly.

**Question:** Which two tasks can Microsoft 365 Copilot in Excel help you complete?

A. Generate a summary of trends and anomalies in the table
B. Rewrite the workbook's VBA macros to optimize performance
C. Build a pivot table based on the data
D. Reconfigure Excel trust center settings for all users

**Correct answer:** A, C

* **A** — Correct because Copilot in Excel is built to analyze structured data and return natural-language insights such as patterns, outliers, trends, and notable movements in the dataset.
* **C** — Correct because Copilot can help create and suggest pivot-table style analysis from tabular data so users can explore summaries faster without manually building everything from scratch.

**Why the other options are incorrect**

* **B** — Incorrect because editing or optimizing VBA code is not a core business-user Copilot-in-Excel capability in this context. The product is focused on data analysis, summarization, and productivity tasks rather than deep macro engineering.
* **D** — Incorrect because tenant-wide or application security configuration is an administrative task, not a Copilot productivity feature for spreadsheet analysis.



\---

## Question 62 — Word

You are drafting a project update in Microsoft Word for senior stakeholders.

**Question:** Which action is the BEST use of Microsoft 365 Copilot in Word?

A. Ask Copilot to summarize the draft and rewrite it in a more executive tone
B. Ask Copilot to change the printer driver settings on your computer
C. Ask Copilot to enforce corporate retention labels across SharePoint
D. Ask Copilot to repair corrupted font files in Windows

**Correct answer:** A

* **A** — Correct because Copilot in Word is designed for drafting, rewriting, summarizing, and changing tone based on audience needs. That is exactly the kind of business-writing task it supports well.

**Why the other options are incorrect**

* **B** — Incorrect because printer driver management is an operating-system task and unrelated to document authoring.
* **C** — Incorrect because retention-label enforcement is a compliance and administration function, not a Word authoring capability.
* **D** — Incorrect because repairing local fonts is a device troubleshooting task outside Copilot in Word.



\---

## Question 63 — Outlook

You open a long email thread with several participants and need to reply quickly.

**Question:** Which Microsoft 365 Copilot capability in Outlook is MOST relevant?

A. Generate a draft response grounded in the conversation context
B. Replace your organization's email security gateway rules
C. Move all mailboxes to a new Exchange region
D. Create new conditional access policies for external users

**Correct answer:** A

* **A** — Correct because Copilot in Outlook can read the thread context and propose a relevant draft reply, saving time while preserving the flow of the conversation.

**Why the other options are incorrect**

* **B** — Incorrect because mail-security gateway rules are infrastructure or security-admin tasks, not end-user Copilot features.
* **C** — Incorrect because mailbox migration is an Exchange administration activity, not a Copilot drafting scenario.
* **D** — Incorrect because conditional access is handled through identity and security administration, not through Outlook Copilot.



\---

## Question 64 — Teams

You missed part of a Microsoft Teams meeting and need the important outcomes.

**Question:** What should you use first in Microsoft 365 Copilot for Teams?

A. Recap or a meeting summary to identify decisions and action items
B. A device firmware update report
C. A tenant migration wizard
D. A custom background generator

**Correct answer:** A

* **A** — Correct because Copilot in Teams is specifically useful for post-meeting catch-up. It can summarize discussion points, decisions, owners, and next steps from meeting content.

**Why the other options are incorrect**

* **B** — Incorrect because firmware reporting is unrelated to meeting intelligence.
* **C** — Incorrect because tenant migration is a platform administration task, not a meeting productivity feature.
* **D** — Incorrect because a custom background does not help identify meeting outcomes or action items.



\---

## Question 65 — PowerPoint

You have a rough outline for a presentation and need help turning it into slides.

**Question:** Which two tasks can Copilot in PowerPoint support most directly?

A. Create a slide draft from your outline
B. Produce a summary slide from the key points
C. Change GPU driver settings for smoother animations
D. Modify the organization's approved brand assets in the admin portal

**Correct answer:** A, B

* **A** — Correct because Copilot in PowerPoint can generate slide content and propose layouts from existing text or outlines.
* **B** — Correct because summarizing the main ideas of a presentation into a concise closing or recap slide is a strong Copilot use case.

**Why the other options are incorrect**

* **C** — Incorrect because device graphics configuration is not part of presentation-generation capabilities.
* **D** — Incorrect because tenant-level brand-asset governance belongs to admins and design processes, not to Copilot's core slide-creation workflow.



\---

## Question 66 — Grounding

You ask Copilot for insights about a proposal stored in SharePoint and want the response to stay faithful to that proposal.

**Question:** What is the BEST prompt strategy?

A. Reference the specific proposal file in the prompt
B. Tell Copilot to guess likely proposal details from its general knowledge
C. Avoid mentioning any source material so the answer is more creative
D. Ask only for a stylish format without specifying the document

**Correct answer:** A

* **A** — Correct because grounding improves when Copilot is pointed to the exact source it should use. Referencing the proposal helps the model base its answer on the intended business content instead of relying mostly on general model knowledge.

**Why the other options are incorrect**

* **B** — Incorrect because asking Copilot to infer missing details increases the risk of unsupported content or hallucinations.
* **C** — Incorrect because omitting the source weakens grounding and makes the response less reliable for business use.
* **D** — Incorrect because output style matters, but it does not solve the core problem of ensuring the response is based on the proposal itself.



\---

## Question 67 — Prompt Engineering

You want Copilot to summarize a partnership proposal into three concise bullets for a kickoff meeting.

**Question:** Which two prompt elements are MOST important?

A. The specific source document to use
B. Clear instructions about the output length and style
C. A random list of stakeholder phone numbers
D. An unrelated company history from ten years ago

**Correct answer:** A, B

* **A** — Correct because Copilot needs to know what content to summarize. Naming or attaching the proposal establishes the source of truth.
* **B** — Correct because specifying 'three concise bullets' tells Copilot exactly how to shape the response for the meeting audience.

**Why the other options are incorrect**

* **C** — Incorrect because contact details do not help Copilot summarize the proposal unless the task explicitly requires them.
* **D** — Incorrect because unrelated historical background adds noise and can reduce prompt quality rather than improve it.



\---

## Question 68 — Security

A merchandiser uses Copilot suggestions based only on historical sales data and places a large order without reviewing the result or checking current market conditions.

**Question:** What does this scenario illustrate?

A. Verification
B. Overreliance on AI output
C. Prompt grounding
D. Tenant isolation

**Correct answer:** B

* **B** — Correct because the user accepted the AI recommendation without applying human judgment or validating it against current business realities. That is the classic pattern of overreliance.

**Why the other options are incorrect**

* **A** — Incorrect because verification would mean checking and validating the AI result before acting on it, which did not happen here.
* **C** — Incorrect because prompt grounding is about connecting a prompt to relevant source material, not blindly trusting an answer.
* **D** — Incorrect because tenant isolation concerns organizational data boundaries, which is not the issue in this business decision scenario.



\---

## Question 69 — Responsible AI

You receive an image that may have been generated with AI and want a trustworthy way to check its provenance.

**Question:** What should you look for first?

A. Content credentials
B. The file name
C. A long image title
D. Whether the sender used uppercase letters in the email

**Correct answer:** A

* **A** — Correct because content credentials are intended to provide provenance details and help indicate whether media was AI-generated or modified.

**Why the other options are incorrect**

* **B** — Incorrect because file names can be changed easily and do not prove origin.
* **C** — Incorrect because titles or descriptions are not a reliable provenance mechanism.
* **D** — Incorrect because sender writing style has nothing to do with verifiable media authenticity.



\---

## Question 70 — Data \& Privacy

A colleague asks how Microsoft 365 Copilot answers questions in Work scope.

**Question:** Which statement is most accurate?

A. Copilot uses all data in the tenant whether the user has permission or not
B. Copilot uses only the user's accessible organizational data plus general model knowledge
C. Copilot uses only public web results
D. Copilot uses the tenant's data to retrain the foundation model before answering

**Correct answer:** B

* **B** — Correct because Work-scope answers are grounded in organizational content the user is already allowed to access, while also benefiting from the model's general reasoning and language capabilities.

**Why the other options are incorrect**

* **A** — Incorrect because Copilot respects existing permissions and does not bypass access controls.
* **C** — Incorrect because Work scope is not limited to public web grounding; it is designed to use work data when available and authorized.
* **D** — Incorrect because tenant data is not used to retrain the underlying model in this scenario.



\---

## Question 71 — Excel

You are reviewing a sales workbook in Microsoft Excel and want to prepare a management update quickly.

**Question:** Which two tasks can Microsoft 365 Copilot in Excel help you complete?

A. Generate a summary of trends and anomalies in the table
B. Rewrite the workbook's VBA macros to optimize performance
C. Build a pivot table based on the data
D. Reconfigure Excel trust center settings for all users

**Correct answer:** A, C

* **A** — Correct because Copilot in Excel is built to analyze structured data and return natural-language insights such as patterns, outliers, trends, and notable movements in the dataset.
* **C** — Correct because Copilot can help create and suggest pivot-table style analysis from tabular data so users can explore summaries faster without manually building everything from scratch.

**Why the other options are incorrect**

* **B** — Incorrect because editing or optimizing VBA code is not a core business-user Copilot-in-Excel capability in this context. The product is focused on data analysis, summarization, and productivity tasks rather than deep macro engineering.
* **D** — Incorrect because tenant-wide or application security configuration is an administrative task, not a Copilot productivity feature for spreadsheet analysis.



\---

## Question 72 — Word

You are drafting a project update in Microsoft Word for senior stakeholders.

**Question:** Which action is the BEST use of Microsoft 365 Copilot in Word?

A. Ask Copilot to summarize the draft and rewrite it in a more executive tone
B. Ask Copilot to change the printer driver settings on your computer
C. Ask Copilot to enforce corporate retention labels across SharePoint
D. Ask Copilot to repair corrupted font files in Windows

**Correct answer:** A

* **A** — Correct because Copilot in Word is designed for drafting, rewriting, summarizing, and changing tone based on audience needs. That is exactly the kind of business-writing task it supports well.

**Why the other options are incorrect**

* **B** — Incorrect because printer driver management is an operating-system task and unrelated to document authoring.
* **C** — Incorrect because retention-label enforcement is a compliance and administration function, not a Word authoring capability.
* **D** — Incorrect because repairing local fonts is a device troubleshooting task outside Copilot in Word.



\---

## Question 73 — Outlook

You open a long email thread with several participants and need to reply quickly.

**Question:** Which Microsoft 365 Copilot capability in Outlook is MOST relevant?

A. Generate a draft response grounded in the conversation context
B. Replace your organization's email security gateway rules
C. Move all mailboxes to a new Exchange region
D. Create new conditional access policies for external users

**Correct answer:** A

* **A** — Correct because Copilot in Outlook can read the thread context and propose a relevant draft reply, saving time while preserving the flow of the conversation.

**Why the other options are incorrect**

* **B** — Incorrect because mail-security gateway rules are infrastructure or security-admin tasks, not end-user Copilot features.
* **C** — Incorrect because mailbox migration is an Exchange administration activity, not a Copilot drafting scenario.
* **D** — Incorrect because conditional access is handled through identity and security administration, not through Outlook Copilot.



\---

## Question 74 — Teams

You missed part of a Microsoft Teams meeting and need the important outcomes.

**Question:** What should you use first in Microsoft 365 Copilot for Teams?

A. Recap or a meeting summary to identify decisions and action items
B. A device firmware update report
C. A tenant migration wizard
D. A custom background generator

**Correct answer:** A

* **A** — Correct because Copilot in Teams is specifically useful for post-meeting catch-up. It can summarize discussion points, decisions, owners, and next steps from meeting content.

**Why the other options are incorrect**

* **B** — Incorrect because firmware reporting is unrelated to meeting intelligence.
* **C** — Incorrect because tenant migration is a platform administration task, not a meeting productivity feature.
* **D** — Incorrect because a custom background does not help identify meeting outcomes or action items.



\---

## Question 75 — PowerPoint

You have a rough outline for a presentation and need help turning it into slides.

**Question:** Which two tasks can Copilot in PowerPoint support most directly?

A. Create a slide draft from your outline
B. Produce a summary slide from the key points
C. Change GPU driver settings for smoother animations
D. Modify the organization's approved brand assets in the admin portal

**Correct answer:** A, B

* **A** — Correct because Copilot in PowerPoint can generate slide content and propose layouts from existing text or outlines.
* **B** — Correct because summarizing the main ideas of a presentation into a concise closing or recap slide is a strong Copilot use case.

**Why the other options are incorrect**

* **C** — Incorrect because device graphics configuration is not part of presentation-generation capabilities.
* **D** — Incorrect because tenant-level brand-asset governance belongs to admins and design processes, not to Copilot's core slide-creation workflow.



\---

## Question 76 — Grounding

You ask Copilot for insights about a proposal stored in SharePoint and want the response to stay faithful to that proposal.

**Question:** What is the BEST prompt strategy?

A. Reference the specific proposal file in the prompt
B. Tell Copilot to guess likely proposal details from its general knowledge
C. Avoid mentioning any source material so the answer is more creative
D. Ask only for a stylish format without specifying the document

**Correct answer:** A

* **A** — Correct because grounding improves when Copilot is pointed to the exact source it should use. Referencing the proposal helps the model base its answer on the intended business content instead of relying mostly on general model knowledge.

**Why the other options are incorrect**

* **B** — Incorrect because asking Copilot to infer missing details increases the risk of unsupported content or hallucinations.
* **C** — Incorrect because omitting the source weakens grounding and makes the response less reliable for business use.
* **D** — Incorrect because output style matters, but it does not solve the core problem of ensuring the response is based on the proposal itself.



\---

## Question 77 — Prompt Engineering

You want Copilot to summarize a partnership proposal into three concise bullets for a kickoff meeting.

**Question:** Which two prompt elements are MOST important?

A. The specific source document to use
B. Clear instructions about the output length and style
C. A random list of stakeholder phone numbers
D. An unrelated company history from ten years ago

**Correct answer:** A, B

* **A** — Correct because Copilot needs to know what content to summarize. Naming or attaching the proposal establishes the source of truth.
* **B** — Correct because specifying 'three concise bullets' tells Copilot exactly how to shape the response for the meeting audience.

**Why the other options are incorrect**

* **C** — Incorrect because contact details do not help Copilot summarize the proposal unless the task explicitly requires them.
* **D** — Incorrect because unrelated historical background adds noise and can reduce prompt quality rather than improve it.



\---

## Question 78 — Security

A merchandiser uses Copilot suggestions based only on historical sales data and places a large order without reviewing the result or checking current market conditions.

**Question:** What does this scenario illustrate?

A. Verification
B. Overreliance on AI output
C. Prompt grounding
D. Tenant isolation

**Correct answer:** B

* **B** — Correct because the user accepted the AI recommendation without applying human judgment or validating it against current business realities. That is the classic pattern of overreliance.

**Why the other options are incorrect**

* **A** — Incorrect because verification would mean checking and validating the AI result before acting on it, which did not happen here.
* **C** — Incorrect because prompt grounding is about connecting a prompt to relevant source material, not blindly trusting an answer.
* **D** — Incorrect because tenant isolation concerns organizational data boundaries, which is not the issue in this business decision scenario.



\---

## Question 79 — Responsible AI

You receive an image that may have been generated with AI and want a trustworthy way to check its provenance.

**Question:** What should you look for first?

A. Content credentials
B. The file name
C. A long image title
D. Whether the sender used uppercase letters in the email

**Correct answer:** A

* **A** — Correct because content credentials are intended to provide provenance details and help indicate whether media was AI-generated or modified.

**Why the other options are incorrect**

* **B** — Incorrect because file names can be changed easily and do not prove origin.
* **C** — Incorrect because titles or descriptions are not a reliable provenance mechanism.
* **D** — Incorrect because sender writing style has nothing to do with verifiable media authenticity.



\---

## Question 80 — Data \& Privacy

A colleague asks how Microsoft 365 Copilot answers questions in Work scope.

**Question:** Which statement is most accurate?

A. Copilot uses all data in the tenant whether the user has permission or not
B. Copilot uses only the user's accessible organizational data plus general model knowledge
C. Copilot uses only public web results
D. Copilot uses the tenant's data to retrain the foundation model before answering

**Correct answer:** B

* **B** — Correct because Work-scope answers are grounded in organizational content the user is already allowed to access, while also benefiting from the model's general reasoning and language capabilities.

**Why the other options are incorrect**

* **A** — Incorrect because Copilot respects existing permissions and does not bypass access controls.
* **C** — Incorrect because Work scope is not limited to public web grounding; it is designed to use work data when available and authorized.
* **D** — Incorrect because tenant data is not used to retrain the underlying model in this scenario.



\---

## Question 81 — Excel

You are reviewing a sales workbook in Microsoft Excel and want to prepare a management update quickly.

**Question:** Which two tasks can Microsoft 365 Copilot in Excel help you complete?

A. Generate a summary of trends and anomalies in the table
B. Rewrite the workbook's VBA macros to optimize performance
C. Build a pivot table based on the data
D. Reconfigure Excel trust center settings for all users

**Correct answer:** A, C

* **A** — Correct because Copilot in Excel is built to analyze structured data and return natural-language insights such as patterns, outliers, trends, and notable movements in the dataset.
* **C** — Correct because Copilot can help create and suggest pivot-table style analysis from tabular data so users can explore summaries faster without manually building everything from scratch.

**Why the other options are incorrect**

* **B** — Incorrect because editing or optimizing VBA code is not a core business-user Copilot-in-Excel capability in this context. The product is focused on data analysis, summarization, and productivity tasks rather than deep macro engineering.
* **D** — Incorrect because tenant-wide or application security configuration is an administrative task, not a Copilot productivity feature for spreadsheet analysis.



\---

## Question 82 — Word

You are drafting a project update in Microsoft Word for senior stakeholders.

**Question:** Which action is the BEST use of Microsoft 365 Copilot in Word?

A. Ask Copilot to summarize the draft and rewrite it in a more executive tone
B. Ask Copilot to change the printer driver settings on your computer
C. Ask Copilot to enforce corporate retention labels across SharePoint
D. Ask Copilot to repair corrupted font files in Windows

**Correct answer:** A

* **A** — Correct because Copilot in Word is designed for drafting, rewriting, summarizing, and changing tone based on audience needs. That is exactly the kind of business-writing task it supports well.

**Why the other options are incorrect**

* **B** — Incorrect because printer driver management is an operating-system task and unrelated to document authoring.
* **C** — Incorrect because retention-label enforcement is a compliance and administration function, not a Word authoring capability.
* **D** — Incorrect because repairing local fonts is a device troubleshooting task outside Copilot in Word.



\---

## Question 83 — Outlook

You open a long email thread with several participants and need to reply quickly.

**Question:** Which Microsoft 365 Copilot capability in Outlook is MOST relevant?

A. Generate a draft response grounded in the conversation context
B. Replace your organization's email security gateway rules
C. Move all mailboxes to a new Exchange region
D. Create new conditional access policies for external users

**Correct answer:** A

* **A** — Correct because Copilot in Outlook can read the thread context and propose a relevant draft reply, saving time while preserving the flow of the conversation.

**Why the other options are incorrect**

* **B** — Incorrect because mail-security gateway rules are infrastructure or security-admin tasks, not end-user Copilot features.
* **C** — Incorrect because mailbox migration is an Exchange administration activity, not a Copilot drafting scenario.
* **D** — Incorrect because conditional access is handled through identity and security administration, not through Outlook Copilot.



\---

## Question 84 — Teams

You missed part of a Microsoft Teams meeting and need the important outcomes.

**Question:** What should you use first in Microsoft 365 Copilot for Teams?

A. Recap or a meeting summary to identify decisions and action items
B. A device firmware update report
C. A tenant migration wizard
D. A custom background generator

**Correct answer:** A

* **A** — Correct because Copilot in Teams is specifically useful for post-meeting catch-up. It can summarize discussion points, decisions, owners, and next steps from meeting content.

**Why the other options are incorrect**

* **B** — Incorrect because firmware reporting is unrelated to meeting intelligence.
* **C** — Incorrect because tenant migration is a platform administration task, not a meeting productivity feature.
* **D** — Incorrect because a custom background does not help identify meeting outcomes or action items.



\---

## Question 85 — PowerPoint

You have a rough outline for a presentation and need help turning it into slides.

**Question:** Which two tasks can Copilot in PowerPoint support most directly?

A. Create a slide draft from your outline
B. Produce a summary slide from the key points
C. Change GPU driver settings for smoother animations
D. Modify the organization's approved brand assets in the admin portal

**Correct answer:** A, B

* **A** — Correct because Copilot in PowerPoint can generate slide content and propose layouts from existing text or outlines.
* **B** — Correct because summarizing the main ideas of a presentation into a concise closing or recap slide is a strong Copilot use case.

**Why the other options are incorrect**

* **C** — Incorrect because device graphics configuration is not part of presentation-generation capabilities.
* **D** — Incorrect because tenant-level brand-asset governance belongs to admins and design processes, not to Copilot's core slide-creation workflow.



\---

## Question 86 — Grounding

You ask Copilot for insights about a proposal stored in SharePoint and want the response to stay faithful to that proposal.

**Question:** What is the BEST prompt strategy?

A. Reference the specific proposal file in the prompt
B. Tell Copilot to guess likely proposal details from its general knowledge
C. Avoid mentioning any source material so the answer is more creative
D. Ask only for a stylish format without specifying the document

**Correct answer:** A

* **A** — Correct because grounding improves when Copilot is pointed to the exact source it should use. Referencing the proposal helps the model base its answer on the intended business content instead of relying mostly on general model knowledge.

**Why the other options are incorrect**

* **B** — Incorrect because asking Copilot to infer missing details increases the risk of unsupported content or hallucinations.
* **C** — Incorrect because omitting the source weakens grounding and makes the response less reliable for business use.
* **D** — Incorrect because output style matters, but it does not solve the core problem of ensuring the response is based on the proposal itself.



\---

## Question 87 — Prompt Engineering

You want Copilot to summarize a partnership proposal into three concise bullets for a kickoff meeting.

**Question:** Which two prompt elements are MOST important?

A. The specific source document to use
B. Clear instructions about the output length and style
C. A random list of stakeholder phone numbers
D. An unrelated company history from ten years ago

**Correct answer:** A, B

* **A** — Correct because Copilot needs to know what content to summarize. Naming or attaching the proposal establishes the source of truth.
* **B** — Correct because specifying 'three concise bullets' tells Copilot exactly how to shape the response for the meeting audience.

**Why the other options are incorrect**

* **C** — Incorrect because contact details do not help Copilot summarize the proposal unless the task explicitly requires them.
* **D** — Incorrect because unrelated historical background adds noise and can reduce prompt quality rather than improve it.



\---

## Question 88 — Security

A merchandiser uses Copilot suggestions based only on historical sales data and places a large order without reviewing the result or checking current market conditions.

**Question:** What does this scenario illustrate?

A. Verification
B. Overreliance on AI output
C. Prompt grounding
D. Tenant isolation

**Correct answer:** B

* **B** — Correct because the user accepted the AI recommendation without applying human judgment or validating it against current business realities. That is the classic pattern of overreliance.

**Why the other options are incorrect**

* **A** — Incorrect because verification would mean checking and validating the AI result before acting on it, which did not happen here.
* **C** — Incorrect because prompt grounding is about connecting a prompt to relevant source material, not blindly trusting an answer.
* **D** — Incorrect because tenant isolation concerns organizational data boundaries, which is not the issue in this business decision scenario.



\---

## Question 89 — Responsible AI

You receive an image that may have been generated with AI and want a trustworthy way to check its provenance.

**Question:** What should you look for first?

A. Content credentials
B. The file name
C. A long image title
D. Whether the sender used uppercase letters in the email

**Correct answer:** A

* **A** — Correct because content credentials are intended to provide provenance details and help indicate whether media was AI-generated or modified.

**Why the other options are incorrect**

* **B** — Incorrect because file names can be changed easily and do not prove origin.
* **C** — Incorrect because titles or descriptions are not a reliable provenance mechanism.
* **D** — Incorrect because sender writing style has nothing to do with verifiable media authenticity.



\---

## Question 90 — Data \& Privacy

A colleague asks how Microsoft 365 Copilot answers questions in Work scope.

**Question:** Which statement is most accurate?

A. Copilot uses all data in the tenant whether the user has permission or not
B. Copilot uses only the user's accessible organizational data plus general model knowledge
C. Copilot uses only public web results
D. Copilot uses the tenant's data to retrain the foundation model before answering

**Correct answer:** B

* **B** — Correct because Work-scope answers are grounded in organizational content the user is already allowed to access, while also benefiting from the model's general reasoning and language capabilities.

**Why the other options are incorrect**

* **A** — Incorrect because Copilot respects existing permissions and does not bypass access controls.
* **C** — Incorrect because Work scope is not limited to public web grounding; it is designed to use work data when available and authorized.
* **D** — Incorrect because tenant data is not used to retrain the underlying model in this scenario.



\---

## Question 91 — Excel

You are reviewing a sales workbook in Microsoft Excel and want to prepare a management update quickly.

**Question:** Which two tasks can Microsoft 365 Copilot in Excel help you complete?

A. Generate a summary of trends and anomalies in the table
B. Rewrite the workbook's VBA macros to optimize performance
C. Build a pivot table based on the data
D. Reconfigure Excel trust center settings for all users

**Correct answer:** A, C

* **A** — Correct because Copilot in Excel is built to analyze structured data and return natural-language insights such as patterns, outliers, trends, and notable movements in the dataset.
* **C** — Correct because Copilot can help create and suggest pivot-table style analysis from tabular data so users can explore summaries faster without manually building everything from scratch.

**Why the other options are incorrect**

* **B** — Incorrect because editing or optimizing VBA code is not a core business-user Copilot-in-Excel capability in this context. The product is focused on data analysis, summarization, and productivity tasks rather than deep macro engineering.
* **D** — Incorrect because tenant-wide or application security configuration is an administrative task, not a Copilot productivity feature for spreadsheet analysis.



\---

## Question 92 — Word

You are drafting a project update in Microsoft Word for senior stakeholders.

**Question:** Which action is the BEST use of Microsoft 365 Copilot in Word?

A. Ask Copilot to summarize the draft and rewrite it in a more executive tone
B. Ask Copilot to change the printer driver settings on your computer
C. Ask Copilot to enforce corporate retention labels across SharePoint
D. Ask Copilot to repair corrupted font files in Windows

**Correct answer:** A

* **A** — Correct because Copilot in Word is designed for drafting, rewriting, summarizing, and changing tone based on audience needs. That is exactly the kind of business-writing task it supports well.

**Why the other options are incorrect**

* **B** — Incorrect because printer driver management is an operating-system task and unrelated to document authoring.
* **C** — Incorrect because retention-label enforcement is a compliance and administration function, not a Word authoring capability.
* **D** — Incorrect because repairing local fonts is a device troubleshooting task outside Copilot in Word.



\---

## Question 93 — Outlook

You open a long email thread with several participants and need to reply quickly.

**Question:** Which Microsoft 365 Copilot capability in Outlook is MOST relevant?

A. Generate a draft response grounded in the conversation context
B. Replace your organization's email security gateway rules
C. Move all mailboxes to a new Exchange region
D. Create new conditional access policies for external users

**Correct answer:** A

* **A** — Correct because Copilot in Outlook can read the thread context and propose a relevant draft reply, saving time while preserving the flow of the conversation.

**Why the other options are incorrect**

* **B** — Incorrect because mail-security gateway rules are infrastructure or security-admin tasks, not end-user Copilot features.
* **C** — Incorrect because mailbox migration is an Exchange administration activity, not a Copilot drafting scenario.
* **D** — Incorrect because conditional access is handled through identity and security administration, not through Outlook Copilot.



\---

## Question 94 — Teams

You missed part of a Microsoft Teams meeting and need the important outcomes.

**Question:** What should you use first in Microsoft 365 Copilot for Teams?

A. Recap or a meeting summary to identify decisions and action items
B. A device firmware update report
C. A tenant migration wizard
D. A custom background generator

**Correct answer:** A

* **A** — Correct because Copilot in Teams is specifically useful for post-meeting catch-up. It can summarize discussion points, decisions, owners, and next steps from meeting content.

**Why the other options are incorrect**

* **B** — Incorrect because firmware reporting is unrelated to meeting intelligence.
* **C** — Incorrect because tenant migration is a platform administration task, not a meeting productivity feature.
* **D** — Incorrect because a custom background does not help identify meeting outcomes or action items.



\---

## Question 95 — PowerPoint

You have a rough outline for a presentation and need help turning it into slides.

**Question:** Which two tasks can Copilot in PowerPoint support most directly?

A. Create a slide draft from your outline
B. Produce a summary slide from the key points
C. Change GPU driver settings for smoother animations
D. Modify the organization's approved brand assets in the admin portal

**Correct answer:** A, B

* **A** — Correct because Copilot in PowerPoint can generate slide content and propose layouts from existing text or outlines.
* **B** — Correct because summarizing the main ideas of a presentation into a concise closing or recap slide is a strong Copilot use case.

**Why the other options are incorrect**

* **C** — Incorrect because device graphics configuration is not part of presentation-generation capabilities.
* **D** — Incorrect because tenant-level brand-asset governance belongs to admins and design processes, not to Copilot's core slide-creation workflow.



\---

## Question 96 — Grounding

You ask Copilot for insights about a proposal stored in SharePoint and want the response to stay faithful to that proposal.

**Question:** What is the BEST prompt strategy?

A. Reference the specific proposal file in the prompt
B. Tell Copilot to guess likely proposal details from its general knowledge
C. Avoid mentioning any source material so the answer is more creative
D. Ask only for a stylish format without specifying the document

**Correct answer:** A

* **A** — Correct because grounding improves when Copilot is pointed to the exact source it should use. Referencing the proposal helps the model base its answer on the intended business content instead of relying mostly on general model knowledge.

**Why the other options are incorrect**

* **B** — Incorrect because asking Copilot to infer missing details increases the risk of unsupported content or hallucinations.
* **C** — Incorrect because omitting the source weakens grounding and makes the response less reliable for business use.
* **D** — Incorrect because output style matters, but it does not solve the core problem of ensuring the response is based on the proposal itself.



\---

## Question 97 — Prompt Engineering

You want Copilot to summarize a partnership proposal into three concise bullets for a kickoff meeting.

**Question:** Which two prompt elements are MOST important?

A. The specific source document to use
B. Clear instructions about the output length and style
C. A random list of stakeholder phone numbers
D. An unrelated company history from ten years ago

**Correct answer:** A, B

* **A** — Correct because Copilot needs to know what content to summarize. Naming or attaching the proposal establishes the source of truth.
* **B** — Correct because specifying 'three concise bullets' tells Copilot exactly how to shape the response for the meeting audience.

**Why the other options are incorrect**

* **C** — Incorrect because contact details do not help Copilot summarize the proposal unless the task explicitly requires them.
* **D** — Incorrect because unrelated historical background adds noise and can reduce prompt quality rather than improve it.



\---

## Question 98 — Security

A merchandiser uses Copilot suggestions based only on historical sales data and places a large order without reviewing the result or checking current market conditions.

**Question:** What does this scenario illustrate?

A. Verification
B. Overreliance on AI output
C. Prompt grounding
D. Tenant isolation

**Correct answer:** B

* **B** — Correct because the user accepted the AI recommendation without applying human judgment or validating it against current business realities. That is the classic pattern of overreliance.

**Why the other options are incorrect**

* **A** — Incorrect because verification would mean checking and validating the AI result before acting on it, which did not happen here.
* **C** — Incorrect because prompt grounding is about connecting a prompt to relevant source material, not blindly trusting an answer.
* **D** — Incorrect because tenant isolation concerns organizational data boundaries, which is not the issue in this business decision scenario.



\---

## Question 99 — Responsible AI

You receive an image that may have been generated with AI and want a trustworthy way to check its provenance.

**Question:** What should you look for first?

A. Content credentials
B. The file name
C. A long image title
D. Whether the sender used uppercase letters in the email

**Correct answer:** A

* **A** — Correct because content credentials are intended to provide provenance details and help indicate whether media was AI-generated or modified.

**Why the other options are incorrect**

* **B** — Incorrect because file names can be changed easily and do not prove origin.
* **C** — Incorrect because titles or descriptions are not a reliable provenance mechanism.
* **D** — Incorrect because sender writing style has nothing to do with verifiable media authenticity.



\---

## Question 100 — Data \& Privacy

A colleague asks how Microsoft 365 Copilot answers questions in Work scope.

**Question:** Which statement is most accurate?

A. Copilot uses all data in the tenant whether the user has permission or not
B. Copilot uses only the user's accessible organizational data plus general model knowledge
C. Copilot uses only public web results
D. Copilot uses the tenant's data to retrain the foundation model before answering

**Correct answer:** B

* **B** — Correct because Work-scope answers are grounded in organizational content the user is already allowed to access, while also benefiting from the model's general reasoning and language capabilities.

**Why the other options are incorrect**

* **A** — Incorrect because Copilot respects existing permissions and does not bypass access controls.
* **C** — Incorrect because Work scope is not limited to public web grounding; it is designed to use work data when available and authorized.
* **D** — Incorrect because tenant data is not used to retrain the underlying model in this scenario.



\---

