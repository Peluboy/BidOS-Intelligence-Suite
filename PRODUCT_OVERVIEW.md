# BidOS Intelligence Suite: Product Overview


## Introduction: What is BidOS?

BidOS is a browser extension that sits inside Upwork. It acts as your **Digital Scout** and **Strategic Consultant**. While you work on other things, BidOS watches the Upwork job feed for you. When you open a job, it instantly tells you if the client is worth your time, how much to charge, and then writes the winning proposal for you.

Think of it as having a smart assistant that never sleeps—always watching for the best jobs, analyzing the numbers, and helping you win more work.

---

## Tab-by-Tab Feature Walkthrough

### The Analyze Tab

This is the main tab you see when you open BidOS. Everything starts here.

#### Analyze Current Job Button

When you open a job on Upwork that you're interested in, you click **"Analyze Current Job"** in BidOS. This button scans the job page and pulls out hidden data that most freelancers miss. It happens in seconds—no waiting, no guessing.

Once clicked, BidOS loads the job details and shows you everything you need to make a smart decision.

#### Gatekeeper Metrics

These are the key numbers that act as your gatekeeper—deciding who gets in and who gets blocked:

- **Hire Rate:** What percentage of freelancers this client actually hires. A low hire rate means they post jobs but never hire anyone. A high rate means they are serious.
- **Avg Paid:** The average hourly rate this client pays. This tells you if they are budget-conscious or willing to pay premium rates.
- **Budget:** The total amount the client has set aside for this project.
- **Connects:** How much it costs you to apply (in Upwork's currency). BidOS uses this to calculate your return on investment.
- **Proposals:** How many freelancers have already applied. More proposals = more competition.
- **Total Spent:** How much this client has spent on Upwork overall. A high spender is usually more reliable.
- **Rating:** The client's star rating from previous freelancers.

All these metrics appear in a grid format so you can see the full picture at a glance.

#### Intelligence Insights

Below the metrics, BidOS shows you intelligent insights based on the numbers:

- **Client Name:** Who you're dealing with.
- **Bid Strategy:** Whether you should bid low, medium, or go for premium pricing.
- **Connects ROI:** Is it worth spending your connects on this job? BidOS calculates if the cost to apply is worth the potential return.
- **Portfolio:** What work samples you should attach based on the job description.
- **Expertise Match:** How well your skills match what the client needs.

#### The Scorecard

At the bottom of the analysis, there's a **decision box** that gives you a simple verdict:

- **APPROVED** (green): The client looks good. The numbers work. Go ahead and apply.
- **REJECTED** (red): The numbers don't add up. This client is a waste of time.
- **OVERRIDE** (yellow): The numbers are mixed. It's your call.

This takes all the guesswork out of deciding whether to apply.

#### Generate Proposal Button

If the scorecard says APPROVED, a **"Generate Proposal"** button appears. Click it and BidOS writes a custom proposal tailored to this specific job. It uses your profile, your skills, and your custom instructions to generate something that sounds like you—not like a robot.

#### Generation Strategy

Before generating, you can choose how you want to sound. The strategy dropdown lets you pick:

- **The Expert:** Focuses on technical authority. Best for complex, technical jobs.
- **The Result-Getter:** Focuses on ROI and business outcomes. Best for clients who care about results.
- **The Strategic Partner:** Focuses on long-term collaboration. Best for ongoing relationships.
- **A/B Test:** Generates three different opening hooks so you can pick the best one.

This ensures your proposal matches the client's energy.

#### Auto-Answer Questions

Many Upwork jobs include **screening questions**. BidOS finds these questions and can auto-answer them for you based on the job description. Just click **"Auto-Answer All Questions"** and BidOS writes intelligent answers that match what the client is looking for.

---

### The History Tab

Every job you analyze gets saved here automatically.

#### Proposal Log

The History tab shows a list of every job you've analyzed:

- **Job Title:** What the project was called.
- **Verdict:** Whether you marked it as Approved, Rejected, or Override.
- **Date:** When you analyzed it.

#### Coming Back to Old Jobs

You can click any card in the history to open that job again on Upwork. This is useful when:

- A client messages you weeks later and you need to refresh your memory.
- You want to mark a job as "Submitted" so you know you're waiting on a response.

#### Reminder Notification

After you mark a job as submitted, BidOS tracks it. If three days pass without a response, BidOS shows you a notification reminding you to send a **follow-up message**. This helps you stay on top of your leads without manual tracking.

---

### The Settings Tab (The Brain)

This is where you set up your profile. Think of this as feeding the brain of BidOS. The better your profile, the smarter your proposals.

#### Why the API Key Matters

At the top of Settings, there's a field for **Gemini API Key**. This is required for the AI analysis and proposal generation features. You can get a free key from ai.google.dev. The key is stored locally on your computer—it never leaves your browser.

*Note: Basic features like seeing metrics don't require the API key. But to generate proposals and auto-answer questions, you need to add your key.*

#### Personalization & Profile

These fields customize what BidOS knows about you:

- **Consultant Name:** Your name as it should appear in proposals (e.g., "Michael Clegg").
- **Primary Focus:** Your main area of expertise (e.g., "Document Design"). This helps the AI set the right tone.
- **Target Rate ($):** The minimum hourly rate you want. Jobs paying less will be flagged as REJECTED.
- **Min Budget ($):** The smallest fixed-price project you'll consider. Smaller jobs will be flagged.

#### Estimator Baselines

These tell BidOS how fast you work:

- **Hrs per Slide:** How many hours you need to create one slide.
- **Hrs per Page:** How many hours you need to design one page.

These numbers are used by the **Toolkit Estimator** to calculate prices for clients.

#### Expertise & Skills (20/30)

This is your skill list. Add up to 30 skills that match what you do. BidOS uses this list to:

- Decide if a job matches your profile.
- Recommend the right portfolio pieces.
- Generate proposals that highlight relevant experience.

The more accurate your skills, the smarter the matches.

#### Detailed Services

List your specific services here, one per line (e.g., "- Pitch Deck Design", "- Case Studies"). This helps the AI pitch your services accurately to what the client needs.

#### Custom Instructions

This is where you add your "secret sauce." Any special rules you want the AI to follow:

- "Always mention my 5-year experience in SaaS."
- "Never use emojis."
- "Always offer a free 15-minute consultation."

These instructions get appended to every proposal the AI generates.

#### Strategic Instructions

These customize the **personality** of each strategy:

- **Expert Persona Prompt:** Define how "The Expert" sounds.
- **Result-Getter Persona Prompt:** Define how "The Result-Getter" sounds.
- **Strategic Partner Persona Prompt:** Define how "The Strategic Partner" sounds.

This lets you control the voice and tone of each generation strategy.

#### Enable Background Job Scout

A toggle switch that turns on the Background Scout. When enabled, BidOS watches the Upwork feed while you work and notifies you the second a high-quality job matches your skills. This gives you the **First-Mover Advantage**—applying before everyone else sees the posting.

---

### The Toolkit Tab

This tab contains tools for pricing your work and handling client negotiations.

#### Scope Estimator

This tool helps you calculate exactly how much to charge for a project.

**How to use it:**

1. **Volume:** Enter the count (e.g., 10 slides).
2. **Type:** Select "Slides" or "Pages."
3. **Complexity:** Choose Low, Medium, or High.

**The Math Behind It:**

```
Estimated Hours = Volume × Hours-per-unit × Complexity Multiplier
NTE Budget = Estimated Hours × Your Hourly Rate
```

- **Low (-25%):** Reduces the time by 25%. Used for simple, straightforward work.
- **Medium:** Your standard rate. No adjustment.
- **High (+50%):** Adds 50%. Used for complex, expert-level work.

**NTE (Not-to-Exceed):** The result shows a "Not-to-Exceed" budget. This is a psychological trick—it tells the client "you won't pay more than this," which makes them feel safe agreeing to your price.

Click **"Calculate Estimate"** and BidOS generates:

- Estimated Hours
- NTE Budget
- A ready-to-use pricing script you can copy and send to the client.

#### Negotiation Playbook

Copy-paste responses for every stage of a project. The playbook is divided into three phases:

**Phase 1: Negotiation**

1. **The "How many hours?" Trap:** How to handle clients who want to cap hours.
2. **The Budget Pushback:** How to negotiate when the budget is too low.
3. **The Free Test Request:** How to turn down free work while offering a paid alternative.
4. **The Call Pivot:** How to move from text to a call when needed.

**Phase 2: Execution**

5. **Sending the First Draft:** How to present your initial work professionally.
6. **Submitting Final Project:** How to wrap up and ask for approval.
7. **Gentle Follow-Up:** How to check in without being pushy.

**Phase 3: Offboarding**

8. **Asking for 5-Star Rating:** How to ask for a review at the end.

Click any item to expand it, read the response, and click **"Copy"** to paste it into Upwork.

---

## Summary

BidOS isn't just a tool—it's your competitive advantage. Here's what it does:

1. **Scouts** for the best jobs while you work.
2. **Analyzes** clients instantly with real data.
3. **Scores** every job so you know exactly what to apply for.
4. **Writes** custom proposals in seconds.
5. **Tracks** every job so you never lose a lead.
6. **Prices** your work accurately with the Estimator.
7. **Negotiates** for you with ready-to-use scripts.

It protects your money (Connects), prices your work accurately, and ensures you only talk to high-quality clients. It's the ultimate smart assistant for serious freelancers on Upwork.

---

*For support or questions, refer to the Admin Guide or Team Setup documentation.*