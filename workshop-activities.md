# VOC Workshop Activities - 45 Minutes

## Overview
You'll work through 3 progressive challenges, building a Voice of Customer automation system for your domain.

---

## Challenge 1: Domain Discovery (10 mins)

### Goal
Understand what customer feedback exists for YOUR domain and identify patterns.

### Inside Claude Code, have this conversation:

**Round 1: Basic Discovery**
```
Read customer_feedback.csv and filter for entries related to [your domain].
Show me:
1. How many feedback entries mention my domain?
2. What are the sentiment breakdowns (positive/negative/critical)?
3. What are the top 3 most common words/phrases customers use?
```

**Round 2: Deep Dive**
```
Now group the [domain] feedback by:
- Quick Service vs Fast Casual vs Full Service segments
- Source (Gong, Zendesk, G2)

What patterns do you see? Are certain segments more vocal about specific issues?
```

**Round 3: First Insights**
```
Based on what you've found, what are the 3 most urgent issues customers 
are experiencing in [domain]? Give me the issues with example quotes.

Create a file called initial_findings.md with your analysis.
Commit it.
```

### Success Criteria
- [ ] You understand what feedback exists for your domain
- [ ] You've identified 3 key pain points
- [ ] You have a committed file with findings

---

## Challenge 2: Build Your Analysis System (15 mins)

### Goal
Create instructions that Claude can follow EVERY WEEK to analyze new feedback automatically.

### Inside Claude Code:

**Step 1: Customize Your Template**
```
Open analysis_instructions.md and update it specifically for [your domain].

Add:
- Domain-specific keywords (e.g., for Scheduling: "shift", "roster", "coverage", "swap", "template", "availability")
- Specific things to look for (e.g., "bulk editing complaints", "multi-location issues")
- Integration mentions to track (e.g., "Toast", "ADP", "Gusto")

Make this template detailed enough that someone else could run it.
```

**Step 2: Test Your Instructions**
```
Now follow the instructions you just created. 
Read customer_feedback.csv, apply the analysis you specified,
and create insights.json with the output.

The JSON should include:
- Top 3 pain points with frequency and quotes
- Top 3 feature requests
- Integration needs mentioned
- Recommended actions based on patterns
```

**Step 3: Review & Iterate**
```
Show me the insights.json you created. 
Based on the output, what's missing? What could be better?

Update analysis_instructions.md to improve the quality,
then regenerate insights.json.
```

**Step 4: Commit Your System**
```
Commit both files with message:
"Complete VOC analysis system for [domain] with initial insights"

Push to GitHub.
```

### Success Criteria
- [ ] analysis_instructions.md is customized for your domain
- [ ] insights.json contains meaningful, actionable insights
- [ ] The system is good enough to run weekly with new data
- [ ] Everything is committed to GitHub

---

## Challenge 3: Automate & Scale (10 mins)

### Goal
Make this system reusable and show how it scales to production.

### Inside Claude Code:

**Step 1: Create a Weekly Report Template**
```
Create a file called weekly_report_template.md that structures
the insights.json data into a readable format for leadership.

Include:
- Executive summary (2-3 sentences)
- Top pain points table
- Feature requests by priority
- Integration needs
- Recommended actions

Then use insights.json to generate this week's report as weekly_report_2024-11-25.md
```

**Step 2: Document the Process**
```
Create a file called AUTOMATION_GUIDE.md that explains:
1. How to run this analysis weekly (the exact prompts to use)
2. Where new data should be added (update customer_feedback.csv)
3. How to generate the weekly report
4. How to improve the instructions over time

Write this for a new PM who's never used Claude Code before.
```

**Step 3: Bonus - Multi-Source Vision**
```
Update analysis_instructions.md to include placeholders for:
- Gong call transcripts (future)
- Zendesk ticket data (future)
- G2 reviews (future)

Add comments showing where each data source would plug in.
This shows the scalability.
```

**Step 4: Final Commit**
```
Commit all new files with message:
"Add weekly reporting system and automation documentation"

Push to GitHub.
```

### Success Criteria
- [ ] Weekly report template created and populated
- [ ] Automation guide documents the full process
- [ ] System shows how it scales to multiple data sources
- [ ] Everything committed and pushed

---

## Bonus Challenge: Cross-Domain Insights (If Time Remains)

### Goal
See how your insights connect with other domains.

```
Review the customer_feedback.csv for ALL domains.
Are there any feedback entries that span multiple domains?

For example:
- Scheduling + Payroll integration issues?
- Tips + Labor compliance mentions?

Create cross_domain_opportunities.md highlighting:
- Feedback that affects multiple teams
- Integration opportunities between domains
- Shared pain points we could solve together
```

---

## Share Out Format (Last 7 mins)

Each team will share (60 seconds):

1. **Your #1 customer pain point** - with a quote
2. **One insight you didn't expect** - what surprised you?
3. **Your automation plan** - how will you use this weekly?

**Show your GitHub repo** - prove it's all there!

---

## What You're Building

By the end of this workshop, you have:

✅ A working VOC analysis system for your domain  
✅ Customized instructions that produce insights automatically  
✅ A weekly report template  
✅ Everything version-controlled in GitHub  
✅ Documentation so anyone can run it  
✅ A scalable system ready for production data  

**Next Steps After Workshop:**
1. Connect real Gong API to pull latest calls
2. Add Zendesk ticket integration
3. Schedule to run every Monday morning
4. Auto-post weekly report to Slack

You just built the foundation for automated customer intelligence. 🎉

---

## Tips for Success

**Move fast:** You have limited time - done is better than perfect

**Talk to Claude naturally:** Don't overthink prompts, just explain what you want

**Iterate quickly:** If output isn't great, immediately say "try again with..."

**Commit often:** Every time something works, commit it

**Help each other:** If another team discovers a great prompt, share it!

**Have fun:** This is about exploring what's possible, not perfection
