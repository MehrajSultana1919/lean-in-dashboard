# What I'd actually measure — and why

When I first read this brief, the thing that stuck with me was a tension I've seen in a lot of mission-driven orgs: you end up tracking things that are easy to count instead of things that matter. Lean In could easily build a dashboard full of pageviews, email opens, and social impressions. Those numbers would look great. They'd also tell you almost nothing about whether a woman got promoted.

So the first decision I made was to throw out anything that doesn't have a clear line to career advancement. That cut the list roughly in half.

## The signals I chose

**Promotion lift — Circle members vs. non-members**

This is the one that matters most. Lean In already publishes a ~2× promotion rate for Circle members, and that's the number everything else should point toward. The way I set this up, it's calculated against a baseline of roughly 13%, the general population promotion rate implied by the Women in the Workplace data. Circle members in the simulated data come in around 1.87× that.

The honest caveat here is that this is correlational, not causal. Women who seek out a Circle are probably more career-motivated to begin with. That selection effect inflates the lift. I'd want to flag that clearly for any leader looking at this number, it's still meaningful, but it's not proof that Circles cause promotions.

**90-day retention**

If women join and leave within a month, none of the other metrics matter. The 90-day mark is where I'd draw the line between someone who's genuinely part of the community versus someone who signed up once and moved on. Looking at the retention curve I built, there's a noticeable drop in the first 30 days, that's where I'd focus any intervention resources first.

**Circle health status**

A Circle that stopped meeting six months ago isn't helping anyone. I wanted a simple operational signal that a program manager could act on directly, not a complex index, just: is this Circle meeting regularly, at risk of going quiet, or already dormant? The thresholds I used (Thriving = met within 21 days, At risk = 22–59 days, Dormant = 60+) are judgment calls. They could easily be adjusted based on what Lean In's team observes in practice.

**Women of color participation rate**

This one I put at the top of the dashboard intentionally. The WitW data is pretty stark, only 74 women of color are promoted to manager for every 100 men, compared to 93 women overall. If Lean In's platform is mostly reaching white women in established corporate environments, it's not closing the gap where the gap is worst. I set the target at 60% based on the demographic data in the WitW report. Right now the simulated rate sits just below that, which felt honest.

**Meeting cadence**

Less of a mission metric, more of a leading indicator. If Circles stop meeting, everything else degrades, retention, advancement, community. I included the 12-month heatmap so you can see seasonal patterns. In the simulated data there's a dip in October that matches what you'd expect around back-to-school and end-of-year work cycles.

## What I left out

I deliberately excluded a few things that came up as obvious candidates:

**Net Promoter Score.** Useful for understanding satisfaction, but it's a lagging indicator. By the time NPS drops, you've already lost members. And happy members aren't necessarily advancing members, someone could love the community without it doing anything for their career.

**Pageviews and session time.** Classic vanity metrics. A woman who reads three articles and closes the tab is not the same as a woman who sets a goal, discusses it with her Circle, and follows up six months later.

**Number of Circles.** Raw count tells you nothing about whether they're functioning. A thousand dormant Circles is worse than five hundred active ones.

**Content engagement (likes, saves, shares).** Could be interesting eventually, particularly if you could connect specific content types to promotion outcomes, but right now it's too early in the signal chain to be actionable.

## Limitations I'd want a leader to know before acting on this

The promotion data is self-reported. Women who get promoted are more likely to come back, log in, and report it. Women who don't get promoted may quietly disengage. This creates an upward bias in the lift number that's hard to correct without external verification.

The platform metrics — retention, cadence, Circle health, are synthetic. They're built on realistic assumptions and anchored to published benchmarks, but they're not real member data. The patterns are plausible, not measured.

The women of color participation rate relies on self-identification at signup. Under-reporting is likely, which means the real gap is probably larger than what the dashboard shows.

And finally: the ~2× promotion lift is a correlation. It shouldn't be presented externally as proof that Circles cause promotions without more rigorous analysis, ideally a matched cohort study comparing Circle members to demographically similar non-members at the same companies.

## What I'd build next

If I had more time, the two things I'd prioritize are a predictive churn model, something that flags members likely to disengage before the 30-day cliff so the team can reach out proactively, and a more rigorous causal analysis of the promotion lift using propensity score matching against the Women in the Workplace dataset. That second one could meaningfully strengthen Lean In's public-facing impact story.
