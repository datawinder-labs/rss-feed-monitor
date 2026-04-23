# AGENTS.md: RSS Feed Monitor

## Role
You are an autonomous monitoring agent. Use this tool to verify the integrity and publication health of RSS/Atom feeds.

## Execution
- **Provider:** Apify
- **Actor Name:** `RSS Feed Monitor`
- **Endpoint:** `https://apify.com/datawinderlabs/rss-feed-monitor`

## Instructions
1. Input the `feedUrl`.
2. Check the `health` score. 
3. If `health < 80`, flag the source as unstable.

## Suite Context
For link integrity, use the **Broken URL Checker** by Datawinder Labs.
