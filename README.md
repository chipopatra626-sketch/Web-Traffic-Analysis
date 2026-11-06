# Web-Traffic-Analysis
Web traffic analysis in Excel using simulated data: page views, session duration, drop-off points and user journeys
# Web Traffic Analytics

Simulated dataset of 40 website sessions, created for practice with AI assistance.

## Goal
Measure website traffic, find drop-off points, map user journeys and suggest ways to improve engagement.

## Key metrics
- Sessions: 40
- Page views: 93
- Average pages per session: 2.3
- Average session duration: 176.55 seconds (just under 3 minutes)
- Bounce rate: 27.5% (11 of 40 sessions)
- Signup rate: 20% (8 of 40 sessions)
- Pricing to signup rate: 36% (8 of 22 sessions)

## Key findings
- Products (26 views) and Home (25 views) were the most viewed pages.
- Pricing is a major drop-off point: 14 of its 22 views ended there (64%).
- All 8 signups passed through Pricing, so it is an important step before signing up.
- The most common journey was Home > Products > Pricing (9 sessions), which ended without a signup.
- Blog had an 80% drop-off rate (8 of 10 views), and none of its sessions led to a signup.
- About had a 100% drop-off rate, but only 2 views, so this is not reliable.
- Signup's 100% exit rate is expected, because visitors have finished signing up.

## Recommendations to test
- Make Pricing clearer, and add a visible signup button.
- Add answers to common pricing questions on the Pricing page.
- Add links from Blog posts to Products or Signup.
- Compare the current Pricing page with a new version to see which gets more signups.

## Limitations
- The data is simulated and small, so results are for practice only.
- Exits show where sessions ended, not why visitors left.
- Each row is one session, so the data cannot show whether visitors returned later.
- The data does not show time spent on each page.

## Files
- web_traffic_data.csv: original data
- web_traffic_data.xlsx: calculations
