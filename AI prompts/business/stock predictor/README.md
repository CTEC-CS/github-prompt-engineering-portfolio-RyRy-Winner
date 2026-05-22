# Stock predictor

> *This prompt is intended for checking the value and predicting future values of companies in the stock market, along with those of possibly competing companies.*

## Overview

The Stock Predictor prompt produces extensive, easy-to-understand, and highly detailed explanations regarding whether it is an optimal time to invest in a specific company. By analyzing a target business alongside its market competitors, it delivers structured insights tailored directly to the user's explicit financial constraints.

This prompt solves the problem of investment uncertainty and analysis paralysis. Instead of sorting through dense, unformatted market data, users receive clean, visually separated alternatives that weigh the pros and cons of a specific stock purchase versus other options in the same field.

It is especially useful for individuals deciding where to deploy their capital, business owners wanting to gauge how well their own company is doing against the competition, or any retail investor looking for a scannable overview of market alternatives. The prompt is effective because it leverages the AI's ability to generate comprehensive data while constraining it to specific price brackets and clear visual structures.

**Best For:**
- Checking if you should buy stock in a company right now
- Checking how well your own company is doing
- People looking for good ways to spend money

**Output:** Extensive, detailed, and bulleted descriptions comparing multiple stock options, designed for quick skimming or deep reading.

---

## Quick Start

### 1. Copy the prompt
Open `prompt.md` and copy the entire template.

### 2. Fill in placeholders
Replace these with your specific information:
- `[company1]` - The primary company you are considering investing in
- `[money]` - The exact amount of money (in dollars) you are willing to spend

### 3. Run in your LLM
Paste into Gemini, Claude, ChatGPT, or your preferred model.

### 4. Review and adapt
Review the bulleted list of alternatives provided. Pay special attention to the competitors the AI suggests within your budget bracket, and cross-reference any specific sources generated during the analysis.

---

## Example Use Cases

The following test cases demonstrate the prompt's capabilities:

1. **Tesla Stock Analysis (V1 Test 1)** - Tested with a $1,000 budget. Delivered very detailed explanations and scored 92/100.
2. **Microsoft Stock Analysis (V1 Test 2)** - Tested with a $1,680 budget. Produced highly detailed data, though MagicSchool noted it to be slightly more information than necessary (Scored 85/100).
3. **Six Flags Stock Analysis (V1 Test 3)** - Tested with a $12,444 budget. Achieved a perfect 100/100 score due to its comprehensive breakdown, specific sources, and clear alternative suggestions.

---

## What Makes This Prompt Effective

**Visually Separated Bullets:** Requesting bulleted explanations ensures the AI breaks down information into scannable chunks, allowing users to skim or read deeply based on interest.

**Flexible Variables & High Reusability:** Designed without a rigid formal framework, it can accept almost any company or input seamlessly, making it highly versatile.

**Budget-Driven Constraints:** Forcing the inclusion of a specific dollar amount restricts the AI from suggesting unrealistic choices, keeping options strictly within relevant price brackets.

**Competitor Context:** Rather than evaluating a single stock in a vacuum, the prompt builds from existing market data to surface competing fields and alternative paths for your capital.

---

## Customization Tips

**For Specific Markets or Fields:**
Include small amounts of previously collected market info within the prompt so the AI knows exactly what foundational background to build from.

**For Varying Price Brackets:**
Adjust the money variable to explore how the AI shifts its recommendations from high-cap stocks to alternative investments as budgets scale.

**Adjusting Detail Level:**
- **How to make output more detailed:** Ask the AI to explicitly include secondary market sources and broader competitor history.
- **How to make output more concise:** Specify a preference for brief summaries, as testing shows the default layout can sometimes provide more information than strictly necessary.

---

## Limitations & Considerations

**What This Prompt Does Well:**
- Generates highly comprehensive and specific investment alternatives.
- Accurately structures outputs into clean, readable bullet points.
- Adapts dynamically to highly varied budget sizes.

**What Requires Human Judgment:**
- Filtering out overly verbose or unnecessary information that the AI occasionally generates.
- Verifying real-time stock valuations, as LLM data can sometimes be delayed or require independent sourcing checks.
- Final financial execution, as the prompt acts as an exploratory tool rather than a certified financial advisor.

**Always:**
- Verify specific sources and alternatives provided by the AI before making financial commitments.
- Double-check real-time pricing to ensure the stock still fits your designated price bracket.

---

## Technical Details

**Framework:** No formal framework (designed for high input flexibility and ease of use)  
**Optimal Model:** MagicSchool / Advanced LLMs (Gemini, Claude, ChatGPT)  
**Average Response Length:** Extensive / Highly Detailed  
**Required Placeholders:** 2 (`[company1]`, `[money]`)  

---

## Version History

**v1.0** ([Date Not Provided]) - Initial release and testing. Successfully evaluated via MagicSchool metrics across three varying test brackets (Tesla, Microsoft, Six Flags), achieving an overall average performance score of 92%.

# ⚠️WARNING!⚠️ 

Do NOT blindly trust AI with your financial decisions. Always fact-check AI before making these decisions.
