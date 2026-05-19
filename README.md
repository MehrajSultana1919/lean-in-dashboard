# Lean In — Leadership Advancement Dashboard

## What this is

A dashboard I built for the Lean In Data Scientist assignment. The brief asked for signals that tell you whether Lean In is actually helping women advance — not just whether women are using the platform. That framing shaped every decision I made here.

The dashboard has two views. Platform health shows the operational signals — retention, Circle activity, engagement depth. Industry context pulls in the real published data from the Women in the Workplace reports, which I used as the benchmark layer. If you want to understand why these metrics matter, the broken rung chart in that second view is the place to start.

## How to run it

Open `dashboard.html` in any browser. Double-click it. That's it — no server, no install, no setup. All the data is embedded in the file itself.

## What's real and what's simulated

I want to be upfront about this because I think it matters.

The industry benchmark charts — the broken rung trend from 2018 to 2024, the pipeline representation numbers, the parity projections — those are real. They come directly from the Women in the Workplace 2024 and 2025 reports published by McKinsey and LeanIn.Org. I didn't invent those numbers.

The platform metrics are simulated. I generated them using a seeded random model anchored to the published baselines — so the promotion lift is pegged to Lean In's own ~2× claim, the retention curve follows a realistic exponential decay, and the Circle health distribution reflects plausible platform dynamics. But they're not real member data. I've labeled everything in the dashboard so it's always clear which is which.

## Tools I used

- Chart.js for all the visualizations
- Plain HTML, CSS, and JavaScript — no framework
- Claude AI for code scaffolding and iteration. I used it heavily: to generate the initial chart code, to debug layout issues, and to think through metric choices. The analytical decisions — what to include, what to cut, how to frame the limitations — those came from me reading the brief and the WitW report carefully.

## What I'd do differently with more time

The thing I most want to build is a predictive churn model. The retention curve shows a steep drop in the first 30 days, and right now there's no way to know which members are at risk before they leave. A simple logistic regression on early engagement signals could give the program team a week or two of warning to reach out.

I'd also want to do a more honest causal analysis of the promotion lift. The 1.87× figure is real and meaningful, but it's a correlation — women who join Circles are probably more career-motivated to begin with. A matched cohort study comparing Circle members to similar non-members at the same companies would either validate the number or force a more careful conversation about what Lean In can actually claim.

## One thing I want you to notice

The WoC participation rate is a top-line KPI, not buried in a filter. I put it there on purpose. If that number is low, the platform is working for the people who already have the most advantages — which is the opposite of what Lean In exists to do. I think it belongs in the first thing a leader sees every week, not in a drill-down.
