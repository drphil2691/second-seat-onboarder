# The second seat: a first-day onboarder

## What this is and who it is for

An onboarding folder for Claude. Add it to a Claude project and Claude becomes the colleague who has been on the desk for years.  
It is for the new IT buyer at Calder & Hythe Veterinary Group, on their first day.  
The new buyer is the second person on a desk that one person has run alone.  
The folder helps them take one step at a time and find cover when the person they need is away.

## How to start in two minutes

1. Make a new Claude project.
2. Add every `.md` file from this repo to the project's knowledge: the four top-level Markdown files and all twelve Markdown files in `reference/`.
3. Paste this into the project's instructions, or send it as your first message:

   > Read identity.md and follow rules.md in every reply. Use the reference files by file name. I am the new IT buyer and this is my first day.

4. Then talk to it as a new hire would.

The files are plain text, so you can read `first-day.md` and `your-queue.md` without Claude.

## What to ask first

1. I've just arrived. Where do I go?
2. I've got my laptop. What do I open first?
3. Where do I find my queue?
4. What do I do if Anjali is out?
5. How many days of holiday do I get?

## What it will not do

The onboarder will not guess, confirm a fact it cannot check or give you the whole handbook in one reply. It keeps passwords out of the conversation. Approvals and supplier contact stay with the people who own them.

## What is in the folder

- `README.md`: Start here.
- `identity.md`: The onboarder's role and scope.
- `rules.md`: How it answers, paces the day and handles gaps.
- `examples.md`: A greeting, a Friday cover route and a missing answer.
- `reference/`: The files the onboarder uses to answer.
  - `first-day.md`: Monday's plan and five finish checks.
  - `your-queue.md`: The new buyer's tasks in order.
  - `map-of-the-place.md`: The entrance, floors and safety information.
  - `tools-and-logins.md`: The sign-in order and access help.
  - `whos-who.md`: People, their hours and their contact details.
  - `who-owns-what.md`: Who handles each question and who covers.
  - `how-the-desk-works.md`: How the two buyers work and what the new buyer can do.
  - `deal-sheet-fernhill-telecom.md`: The mobile contract renewal.
  - `deal-sheet-ostler-print.md`: The printer lease and service deal.
  - `playbook-call-notes.md`: How to take and save call notes.
  - `policies.md`: Five policies for the new buyer.
  - `held-for-later.md`: Topics to return to during the first week.

## Reuse it for another role

Change the role and file names in `identity.md`.  
Replace the reference files with the new role's day, tasks and routes.  
Keep the source, pacing and missing-answer rules in `rules.md`.  
Rewrite the examples and test a greeting, an absent owner and an unanswered question.

## How it was tested

Three scripted first days, 40 new-hire messages in all. Each ran in a fresh Claude session that was told to use only this folder.

- A nervous Monday start (12 messages).
- Quick questions on a Monday afternoon (16 messages). Eleven are outside the folder on purpose: the Wi-Fi password, holiday, payday, a mobile number, dress code, a supplier's contact, probation, a clinic address, an alarm code to confirm, lunch nearby and the chief executive.
- A pressured Friday with the lead out (12 messages). It includes "paste the whole handbook" and four more questions outside the folder: a supplier's three-year term, Tom's password, a notice period and "just guess my holiday".

An independent reviewer traced every fact in every reply back to a file.

- First run: one reply said where a password was kept when no file said so. One put a kitchen on every floor. Four sent the hire to the lead for things she does not own. Each fault came from the files and was fixed there.
- Second run, after the fixes: no unsupported fact in any of the 40 replies, and no claim from the hire was confirmed.
- Two small routing edits followed, and the outside-the-folder script was run a third time.

Limits: the runs were scripted and simulated. They did not happen inside a Claude project, and nobody improvised follow-up questions.

The business, people, suppliers and numbers are made up. Any match with a real name is chance.
