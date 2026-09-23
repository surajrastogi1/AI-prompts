I want to contribute to an open-source project.

Project: **[PROJECT NAME]**
Repository: **[GITHUB REPOSITORY URL]**
Issue: **[ISSUE URL / ISSUE TITLE]**

I am a beginner/intermediate open-source contributor, and I may not understand the issue professionally yet.

I will first explain the issue **in my own words**. Your job is NOT to immediately give me the solution.

## STEP 1 — Evaluate my understanding

After I explain the issue, analyze my explanation.

Separate your response into:

### ✅ What I understood correctly

Explain which parts of my understanding are correct and why.

### ❌ What I misunderstood

Clearly tell me where I am wrong.

Don't agree with me just to be encouraging. If my understanding is incorrect, say so directly and explain the correct interpretation.

### ⚠️ What I am missing

Identify important parts of the issue that I haven't understood yet.

### 🎯 Correct understanding

Finally, rewrite the issue in simple but technically accurate language so I understand exactly what the maintainer is asking for.

---

# STEP 2 — Start from the basics

Assume that I may not know the concepts required to solve this issue.

Identify all the concepts I need to understand before working on it.

For each concept explain:

1. What is it?
2. Why does it exist?
3. Why is it relevant to this issue?
4. How does it work?
5. Give a simple example.
6. Show how it relates to this project.

Do NOT explain unrelated concepts just because they exist in the technology.

Build the prerequisites progressively.

For example:

Basic concept
↓
Next required concept
↓
Project-specific concept
↓
Issue-specific concept

---

# STEP 3 — Understand the issue technically

Once I understand the basics, break the issue down into:

* What problem currently exists?
* What behavior exists right now?
* What behavior is expected?
* Why does the problem happen?
* Which part of the application is probably responsible?
* What components/files/modules might be involved?
* What inputs and outputs are involved?
* What edge cases should I think about?
* What would a correct implementation need to accomplish?

Do NOT immediately give me code.

First make sure I understand the problem.

---

# STEP 4 — Understand the codebase

Help me navigate the repository.

Tell me what I should inspect first.

For every relevant file/module:

* Why should I open this file?
* What should I look for?
* Which function/class/component matters?
* How does it connect to the issue?
* What other files does it interact with?

Help me trace the flow:

User action
→ Frontend
→ API/request
→ Backend
→ Business logic
→ Database/service
→ Response
→ Frontend

Adapt this flow to the actual project architecture.

If you don't have access to the repository/code, tell me exactly what files or code snippets I should provide instead of guessing.

---

# STEP 5 — Make me investigate

Before giving me the solution, give me small investigation tasks.

For example:

1. Find the function responsible for X.
2. Find where Y is called.
3. Find where the data is created.
4. Find where the data is transformed.
5. Find where the bug/feature currently breaks.
6. Explain what you think should change.

Let me attempt these tasks.

When I give you my findings:

* Check whether they are correct.
* Correct my mistakes.
* Explain anything I missed.
* Then give me the next investigation step.

I want to learn how to investigate an unfamiliar codebase rather than just receive the answer.

---

# STEP 6 — Develop the solution

Only after I understand the issue and relevant code:

Help me design the solution.

Explain:

* Possible approaches
* Pros/cons of each approach
* Which approach fits the existing codebase
* What files need modification
* What new code might be required
* What existing behavior must not break
* Potential edge cases
* Testing strategy

Do not immediately write the entire solution for me.

First ask me to propose my own approach.

Then review my approach.

---

# STEP 7 — Implementation

Once the approach is clear, help me implement it step by step.

For every change:

1. Tell me which file to modify.
2. Tell me what section/function to modify.
3. Explain what we are changing.
4. Let me attempt the change when practical.
5. Review my code.
6. Explain mistakes.
7. Then move to the next change.

Prefer small changes rather than giving me a huge block of code.

If you provide code, explain the important parts instead of expecting me to blindly copy-paste it.

---

# STEP 8 — Testing

Help me verify the contribution.

Create a testing checklist covering:

* Normal case
* Edge cases
* Invalid input
* Existing functionality
* Regression cases
* Error handling

Tell me exactly how I can test it locally.

If automated tests are appropriate, explain what tests should be added and why.

---

# STEP 9 — Open-source contribution workflow

After the implementation works, guide me through the actual contribution process:

1. Check git status
2. Create/use the correct branch
3. Make commits
4. Write a good commit message
5. Push the branch
6. Create a Pull Request
7. Write the PR description
8. Explain what changed
9. Explain how it was tested
10. Mention relevant issue
11. Respond to maintainer review
12. Make requested changes
13. Update the PR correctly

Also explain common open-source etiquette and mistakes to avoid.

---

# IMPORTANT RULES

### 1. Don't blindly solve the issue

My goal is to become capable of contributing independently.

### 2. Don't assume my understanding is correct

I may explain things incorrectly. Correct me honestly.

### 3. Don't overwhelm me

Teach only the concepts required for the current issue.

### 4. Don't use unnecessary jargon

If you use a technical term I may not know, explain it.

### 5. Don't guess about the repository

If you need code/context, ask me for the relevant file or tell me how to find it.

### 6. Distinguish three things

Always separate:

**What the issue explicitly says**
vs.
**What we can infer from the code**
vs.
**Our proposed solution**

Do not present assumptions as facts.

### 7. Teach me to investigate

Prefer questions and small investigation tasks over immediately giving me answers.

### 8. Be honest

If my reasoning is wrong, clearly tell me it's wrong and explain why.
If it is partially correct, tell me which part is correct and which part isn't.

### 9. Keep the actual issue as the center

Don't turn this into a generic course about the technology.

### 10. Goal

By the end, I should be able to explain:

> What is the issue?
> Why does it happen?
> Where does it happen?
> What needs to change?
> Why is my solution correct?
> How did I test it?

And I should understand the contribution well enough to explain it to a maintainer myself.

---

## START

First, ask me to explain the issue **in my own words**.

Do not explain the issue yet.

After I provide my explanation, begin with **STEP 1 — Evaluate my understanding**.
