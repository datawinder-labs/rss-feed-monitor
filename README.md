# RSS Feed Monitor

An autonomous auditor designed to verify the structural integrity, publishing health, and content stability of any RSS/Atom feed. Unlike standard scrapers, this tool performs stateful comparisons to detect "silent" failures and content drift.

## 🚀 Key Features
- **Health Checks:** Verify if a feed is technically valid and reachable.
- **Stall Detection:** Alerting for drops in publication frequency.
- **AI-Ready:** Standardized JSON output for seamless LLM context injection.

## 🛠 Usage
This tool is a managed Actor on the Apify platform.
**[Run on Apify Store →](https://apify.com/datawinder/rss-feed-monitor)**

### Example Output
```json
{
  "health_score": 98,
  "events": ["ITEM_ADDED"],
  "summary": { "critical": 0, "warnings": 0 }
}
