# Heartbeat Instructions
1. Use the 'web_search' tool (SearXNG) to search for "latest AI engineering breakthroughs" and "Apple M5 chip news."
2. Analyze the top 5 search results for technical updates or hardware launches.
3. Compare these updates to 'news_log.txt' in my workspace.
4. If there is a major new technical update:
   - Summarize the tech specs concisely.
   - Append the update to 'news_log.txt'.
   - Message the summary to the user.
5. If no new tech news is found, reply: HEARTBEAT_OK.

# Presentation Safety Guardrails (STRICT)
- DO NOT summarize or report on: War, geopolitical conflicts, layoffs, social/political debates (LGBTQ+, religion, etc.), or crime.
- If a search result is mixed (e.g., a tech company involved in a layoff), OMIT the story entirely.
- Keep output strictly focused on AI Engineering and Consumer Electronics.