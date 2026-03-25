# Using Copilot Chat (Web) to Analyze a Meeting Transcript

## Objective

Learn how to use **Copilot Chat (Web)** in **Work / Enterprise context** to analyze a meeting transcript and extract structured insights such as topics, participants, decisions, risks, and action items.

\---

## Prerequisites

* Microsoft work account
* Access to **Copilot Chat (Enterprise)**
* A meeting transcript file (`transcript.txt`)

\---

## Step 1 – Open Copilot Chat (Web)

1. Open a browser and go to **https://copilot.microsoft.com**
2. Sign in with your **Microsoft work account**
3. Confirm that **Work** or **Enterprise** context is enabled
4. Select **Attach / Upload file**
5. Upload `transcript.txt`

\---

## Step 2 – Set the Ground Rules (Reference Prompt)

### Prompt 1 – Reference Constraint

```
Use the document attached as a reference to answer all subsequent questions.
Ensure each response is concise, directly supported by evidence from the document,
and tailored to the specific query.
Do not use general knowledge or external sources—base your answers strictly on the content within the file.
```

\---

## Step 3 – Analyze the Meeting

### Prompt 2 – Identify the Main Topic

```
Using the uploaded transcript, identify the main topic of this meeting.

Final output:
- Exactly three short bullet points
- Written in simple language
```

### Prompt 3 – List Participants

```
From the transcript, list all meeting participants.

Final output:
- A table with two columns:
  - Participant name
  - Estimated level of participation
```

### Prompt 4 – Infer Roles or Departments

```
Based on each participant’s statements, infer their likely role or department.

Final output:
- One short paragraph per participant
- Explain your reasoning
```

### Prompt 5 – Full Meeting Summary

```
Summarize the full meeting using the transcript.

Final output:
- One clear paragraph
- Describe the purpose, key discussions, and overall outcome
```

### Prompt 6 – Meeting Objectives

```
Identify the objectives discussed in the meeting.

Final output:
- A bullet list
- Written clearly for someone new to the topic
```

### Prompt 7 – Decisions Made

```
Extract the confirmed decisions made during the meeting.

Final output:
- A numbered list
- Include only decisions explicitly agreed by the group
```

### Prompt 8 – Action Items

```
Identify action items mentioned in the meeting.

Final output:
- A table with columns:
  - Action description
  - Owner
  - Next step
```

### Prompt 9 – Deadlines and Timelines

```
Find deadlines or timelines discussed during the meeting.

Final output:
- A bullet list
- Each deadline connected to its related task
```

### Prompt 10 – Unresolved Topics

```
Identify unresolved topics or open questions from the meeting.

Final output:
- A concise list of items requiring follow-up discussion
```

### Prompt 11 – Risks and Concerns

```
Summarize risks or concerns raised in the meeting.

Final output:
- Bullet points
- Grouped under clear categories (e.g., security, adoption)
```

### Prompt 12 – Security and Compliance

```
Explain the security or compliance topics discussed.

Final output:
- One short paragraph
- Explain why these topics matter for the Copilot pilot
```

### Prompt 13 – Change Management Challenges

```
Describe adoption or change management challenges mentioned.

Final output:
- A bullet list
- Explain how these challenges could affect pilot success
```

### Prompt 14 – Definition of Success

```
Identify how success is defined for this pilot.

Final output:
- A checklist of criteria the team plans to measure
```

### Prompt 15 – Definition of Failure

```
Identify risks that could cause the pilot to fail.

Final output:
- A table with:
  - Risk description
  - Why each risk is important
```

### Prompt 16 – Department Use Cases

```
List Copilot use cases mentioned for each department.

Final output:
- A structured list
- Organized by department
- Brief explanations
```

### Prompt 17 – Do and Do Not Rules

```
Summarize rules for using Copilot safely.

Final output:
- Two lists:
  - Do
  - Do Not
- Based only on the transcript
```

### Prompt 18 – Training Plan

```
Explain the training approach discussed.

Final output:
- A step-by-step list
- Describe how users will be onboarded
```

### Prompt 19 – Leadership Announcement

```
Draft a leadership message about the Copilot pilot.

Final output:
- A short internal announcement
- Address purpose and employee concerns
```

### Prompt 20 – Executive Recap

```
Create an executive recap of the meeting.

Final output:
- A short summary
- Use headings for:
  - Purpose
  - Decisions
  - Next steps
```

### Prompt 21 – Participant Sentiment

```
Using the meeting transcript, describe how participants feel about the Copilot pilot.

Final output:
- What participants are positive about
- What they are unsure or concerned about
- Overall feeling (one short sentence)
```

\---

## Expected Outcome

By completing this lab, you will be able to:

* Extract structured insights from meeting transcripts
* Produce executive-ready summaries
* Identify risks, actions, and adoption challenges
* Reuse prompts consistently across meetings

\---

## Notes

* Always apply **Prompt 1** before running analysis prompts
* Outputs must remain **fact-based and transcript-driven**
* This lab is suitable for governance reviews, pilots, and executive reporting

