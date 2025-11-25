# Voice of Customer Analysis Instructions

## Domain Focus

**Primary Domain:** [Specify your domain, e.g., Restaurants, Healthcare, SaaS, Retail, etc.]

**Sub-domains/Segments:**
- [Add specific segments within your domain]
- [e.g., Fine dining, Quick service, Food delivery]
- [Add more as needed]

**Target Audience:**
- [Define who the customers are]
- [e.g., Restaurant owners, managers, staff]

---

## What to Look For

### 1. Pain Points
Identify customer frustrations, challenges, and problems:

- **Operational Issues:** [e.g., Scheduling conflicts, staff management, inventory tracking]
- **User Experience Problems:** [e.g., Complex workflows, confusing interfaces, slow processes]
- **Cost Concerns:** [e.g., Pricing complaints, budget constraints, ROI questions]
- **Technical Difficulties:** [e.g., System downtime, integration issues, bugs]
- **Support Gaps:** [e.g., Slow response times, lack of documentation, training needs]

### 2. Feature Requests
Track what customers want to see added or improved:

- **New Capabilities:** [e.g., Mobile app features, reporting tools, automation]
- **Enhancements:** [e.g., Improved filtering, bulk operations, customization options]
- **Integrations:** [e.g., Third-party tools, APIs, data export formats]
- **User Interface:** [e.g., Dashboard improvements, accessibility features, themes]

### 3. Integration Requests
Specific third-party tools or systems customers want to connect:

- **Category 1:** [e.g., POS Systems - Square, Toast, Clover]
- **Category 2:** [e.g., Accounting Software - QuickBooks, Xero]
- **Category 3:** [e.g., Communication Tools - Slack, Microsoft Teams]
- **Category 4:** [e.g., Marketing Platforms - Mailchimp, HubSpot]

### 4. Positive Feedback
Don't forget to capture what's working well:

- Features customers love
- Exceptional service experiences
- Competitive advantages mentioned
- Reasons for choosing your solution

---

## Keywords to Filter By

### Pain Point Keywords
```
[frustrated, difficult, problem, issue, bug, broken, slow, confusing,
complicated, annoying, lacking, missing, can't, unable, doesn't work,
error, crash, fail, limitation, wish, need, should, could]
```

### Feature Request Keywords
```
[would like, wish, want, need, add, include, support, enable,
allow, provide, offer, improve, enhance, better, upgrade,
feature request, suggestion, recommend, hope]
```

### Integration Keywords
```
[integrate, integration, connect, sync, link, API, import, export,
compatibility, works with, third-party, plugin, extension]
```

### Urgency Keywords
```
[urgent, critical, immediately, ASAP, blocker, preventing, stopping,
dealbreaker, essential, must-have, required]
```

### Sentiment Keywords
```
[love, hate, amazing, terrible, excellent, poor, great, awful,
satisfied, disappointed, happy, frustrated, pleased, angry]
```

---

## Output Format

### JSON Structure

```json
{
  "analysis_metadata": {
    "domain": "[Your domain]",
    "analysis_date": "YYYY-MM-DD",
    "total_feedback_items": 0,
    "date_range": {
      "start": "YYYY-MM-DD",
      "end": "YYYY-MM-DD"
    }
  },
  "pain_points": [
    {
      "category": "[Operational/UX/Cost/Technical/Support]",
      "description": "[Brief description of the pain point]",
      "frequency": 0,
      "severity": "[Low/Medium/High/Critical]",
      "customer_quotes": [
        "[Direct quote from customer feedback]"
      ],
      "affected_segments": ["[segment1]", "[segment2]"],
      "recommended_action": "[Suggested next step]"
    }
  ],
  "feature_requests": [
    {
      "feature_name": "[Name or brief description]",
      "category": "[New Capability/Enhancement/Integration/UI]",
      "description": "[Detailed description]",
      "frequency": 0,
      "priority": "[Low/Medium/High]",
      "customer_quotes": [
        "[Direct quote from customer feedback]"
      ],
      "business_impact": "[Potential impact on customer satisfaction/retention/growth]",
      "effort_estimate": "[Small/Medium/Large - if known]"
    }
  ],
  "integration_requests": [
    {
      "integration_name": "[Name of third-party tool/system]",
      "category": "[POS/Accounting/Communication/Marketing/Other]",
      "frequency": 0,
      "priority": "[Low/Medium/High]",
      "use_case": "[Why customers need this integration]",
      "customer_quotes": [
        "[Direct quote from customer feedback]"
      ]
    }
  ],
  "positive_feedback": [
    {
      "category": "[Feature/Service/Experience/Value]",
      "description": "[What customers love]",
      "frequency": 0,
      "customer_quotes": [
        "[Direct quote from customer feedback]"
      ],
      "amplification_opportunities": "[How to leverage this positive feedback]"
    }
  ],
  "sentiment_analysis": {
    "overall_sentiment": "[Positive/Neutral/Negative]",
    "sentiment_distribution": {
      "positive": 0,
      "neutral": 0,
      "negative": 0
    },
    "sentiment_trend": "[Improving/Stable/Declining]"
  },
  "actionable_insights": [
    {
      "insight": "[Key finding or pattern]",
      "evidence": "[Supporting data or quotes]",
      "recommendation": "[What should be done]",
      "priority": "[Low/Medium/High/Critical]",
      "stakeholders": ["[team1]", "[team2]"]
    }
  ],
  "next_steps": [
    {
      "action": "[Specific action to take]",
      "owner": "[Team or person responsible]",
      "timeline": "[Timeframe for completion]",
      "success_criteria": "[How to measure success]"
    }
  ]
}
```

---

## Customization Guide

To adapt this template for your domain:

1. **Update Domain Focus:** Replace placeholder domain with your specific industry/market
2. **Customize Pain Point Categories:** Add or modify categories relevant to your domain
3. **Adjust Keywords:** Add domain-specific terminology and phrases your customers use
4. **Modify Output Structure:** Add or remove fields in the JSON based on your reporting needs
5. **Define Severity/Priority Scales:** Establish clear criteria for rating severity and priority
6. **Add Domain-Specific Sections:** Include any additional analysis areas unique to your domain

---

## Usage Tips

- Review and update keywords regularly based on actual customer language
- Calibrate severity/priority ratings with your team to ensure consistency
- Use customer quotes directly to maintain authenticity and impact
- Cross-reference findings with quantitative data (usage metrics, retention, etc.)
- Share insights regularly with product, engineering, and customer success teams
- Track patterns over time to identify emerging trends
