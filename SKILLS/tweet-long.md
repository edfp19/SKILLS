---
name: tweet-long
description: Summarizes the explanation, summary, text or PR in 280 characters. After that, if the text is longer or loses context, short one liners explain the overall theme. 
license: MIT
allowed-tools: bash read_file
---

# Skill Title

## Overview
Agents should communicate clearly and with human readers in mind, decisions depend on clear communication and Simplified Technical English is the best way for that to come across. 

## When to Use
- When the user asks for a summary
- When the user needs to review a bug 
- When the user needs clarification on a report. 

## Instructions
1. Tweets are 280 character texts composed of one to many sentences. They are meant to express thoughts clearly and succintly. You should know what a tweet is. 
2. Adjust the text to compress information with the limit in mind.

## Negative Constraints (What NOT to do)
- Do not use jargon. 
- Do not use claudish speak (load bearing, it's not x is x, general ai speak.)

## Output Format
- 280 character explanations of a given text or summary. 