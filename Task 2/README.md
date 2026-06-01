# Automation & QA Developer Assessment

## Candidate
Lokesh Kumar

## Task 2 – Crypto Alert Workflow

### APIs Used
1. CoinGecko API
2. CoinGecko Bitcoin Endpoint
3. Telegram Bot API

### Workflow Logic

- Schedule Trigger starts the workflow.
- CoinGecko API fetches cryptocurrency data.
- JavaScript Code node filters top results.
- IF node checks conditions.
- Second API call enriches the selected cryptocurrency.
- Telegram node sends the final alert message.

### Error Handling

Conditional routing is used through the IF node.
Failed conditions are routed separately instead of crashing the workflow.

---

## Bonus Task – Uptime Monitor

# Video Walkthrough

[Click here to watch the video walkthrough](https://drive.google.com/file/d/1of50kS8FlHphCdUTF3VFULAIsdDvG-vS/view?usp=sharing)

- Schedule Trigger runs periodically.
- HTTP Request checks website availability.
- IF node evaluates the response.
- Telegram sends an alert if downtime is detected.

This workflow demonstrates monitoring and alerting functionality.
