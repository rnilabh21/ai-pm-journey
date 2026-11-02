# Problem 1: Money app

## Wedge
Type one casual sentence ("coffee 180, cab 340") and get split,
categorised entries. A weekly summary says whether we are on track.
At the start of month I should allocate budget ie my salary into investment, necessary expenditure, leisure, avoidable expenditure, loans
So whenever i make an entry, i should be able to categorise into these 5 tickets

## Users
- Me (primary)
- My wife (primary)
- 3 outside users to be added around Day 68

## Privacy rules
1. Never commit API keys or real expense data to GitHub.
2. Never enter account or card numbers.
3. Check the LLM provider's current data-retention terms before
   sharing the app with anyone beyond us.

## Metrics
- Usage: at least 80% of days with a real expense or a "no spend"
  tap, both users, over 4 weeks.
- Quality: categorisation matches my manual labels on at least 90%
  of 50 real entries.
- Speed: logging an expense takes 10 seconds or less.

## Open questions
- How do we track money today?
- What is "the target"?
