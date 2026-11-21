# From Paper to E-Approval: A Change Management Case Study

**How I moved our payment approvals from paper to an online system, and what I learned when people found it harder to use than we expected.**

📄 **[Read the full case study (PDF, 16 slides)](From%20Paper%20to%20E-Approval%20A%20Change%20Management%20Case%20Study.pdf)**

---

## At a glance

| | |
|---|---|
| **Company** | Car distributor, dealer and after-sales service company, Yangon |
| **My role** | IT Officer, running the internal side of the project |
| **Period** | 2023–2024, about 6 months from proposal to go-live |
| **Scope** | 11 departments, about 20 approvers, up to 6 approval steps per request |
| **Result** | Approval time dropped from **half a day or more** to **under 15 minutes**, with no paper forms |

## The situation

Every payment approval was on paper. Someone printed the form, walked it from office to office for signatures, and mailed or emailed it to department heads who were often travelling. Requests sat on desks while approvers were away, so one approval could take half a day or more.

I proposed moving approvals to an online system at our **weekly Kaizen meeting**, where all department heads and line managers meet to improve how we work. I then led the project discussion at that meeting every week until go-live.

## What I did

- **Requirements and budget:** found out what each team needed and estimated the cost before we started
- **Process design:** agreed the approval flows with Accounting and Finance, including different approval chains depending on the payment amount, and listed every requester and approver
- **Build:** worked with the software vendor on setup, checked the AWS design with the outsourced hosting team, and set practical rules such as file size limits for invoices and payment slips
- **Testing:** tested the system and checked it was easy to use
- **Launch:** organised Zoom training at times that suited users and led the sessions, while the vendor's business analyst presented the system
- **After launch:** helped users with problems and checked the monthly AWS bill

## What went wrong

The system itself worked. The problem was people. Many users didn't know how to create an account or an e-signature, and some started sending requests from other people's accounts.

I used frameworks from my Change Management and Consultancy Skills courses at AIT to understand why:

- **ADKAR:** most gaps were in *Awareness* (why do I need my own account?), *Knowledge* (how do I make an e-signature?) and *Ability* (users couldn't create accounts themselves). *Reinforcement* worked, because nobody went back to paper.
- **Commitment curve:** people knew paper was going away, but many were stuck at the "understanding" stage.
- **Issue tree:** three root causes: **access**, **understanding** and **involvement**. We worked closely with the process owners but not enough with everyday users before launch.

## How we fixed it

- Explained to each department why everyone needs their own account and how its approval steps work
- Helped people create accounts and set up e-signatures
- Ran training once the system was stable

Using the **Head, Heart, Hand** model, we covered the logic (head) and made it easy (hand), but missed the emotional side (heart): showing people what was in it for them.

## Results

| Area | Before | After |
|---|---|---|
| Approval time | Half a day or more | Less than 15 minutes |
| Documents | Printed, carried or mailed | Online, with invoices and payment slips uploaded |
| Tracking | Hard to know where a form was | Approvers can see which step a request is at |

## What I'd do differently

1. **Talk to users early**, not only the people who own the process
2. **Fix access first:** create accounts and e-signatures before launch day
3. **Pick a helper in each team** that colleagues can go to
4. **Show what's in it for them:** no more walking forms around or waiting for travelling bosses
5. **Track adoption weekly:** share of requests sent online, users with their own account, requests from shared accounts and IT support requests. During the project we only tracked approval time.

> **Biggest lesson:** "Organisations don't change, people do." A new system doesn't change how people work by itself.

---

## Frameworks used

Kaizen and lean waste (motion, transport, waiting) · Change context factors · Stakeholder mapping · ADKAR (Prosci) · Patterson–Conner Commitment Curve · Issue tree · Head, Heart, Hand

These come from the Change Management (2025) and Consultancy Skills (2026) courses in my MSc in Business Analytics & Digital Transformation at the Asian Institute of Technology.

*Based on my own experience on the project. Company details are kept general, and the payment amount limits are left out.*
