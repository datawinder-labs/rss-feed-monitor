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
[
  {
    "type": "run_summary",
    "feedId": "6a418c5313a09d59",
    "feedUrl": "https://hnrss.org/frontpage",
    "runId": "MjsYubyL0aSBP7l1Q",
    "timestamp": "2026-04-23T15:15:43.930Z",
    "summary": {
      "totalEvents": 0,
      "critical": 0,
      "warning": 0,
      "info": 0
    },
    "health": {
      "previous": 90,
      "current": 90.2,
      "delta": 0.2
    },
    "events": [],
    "metrics": {
      "previousItemCount": 20,
      "currentItemCount": 20,
      "overlapCount": 20,
      "processingTimeMs": 4694
    }
  }
]
```
