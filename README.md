# Lean In Leadership Advancement Dashboard

Hi there! I built this dashboard as part of the Lean In Data Scientist assignment. The brief wasn’t just about tracking usage it asked a much more important question: *“Is Lean In actually helping women advance?”* That question shaped everything I did here, from which metrics I chose to how I displayed them.

Let me walk you through it.

## Two main views

When you open the dashboard, you’ll see two perspectives:

**Platform Health** shows how the platform itself is performing. Here you can see retention trends, Circle activity, and engagement depth. These signals give a sense of whether members are really getting value over time, not just signing up.

**Industry Context** pulls in published data from the *Women in the Workplace* reports. I used this as a benchmark to see how Lean In compares to the broader industry. The broken rung chart in this view is especially important, it helps explain why these metrics matter and where gaps still exist.

## How it works

Opening the dashboard is as easy as double-clicking `dashboard.html` in your browser. There’s no server, no installation, no setup. Everything runs locally because all the data is embedded right in the file.

## What’s real and what’s simulated

I want to be transparent about this.

The industry benchmarks, like broken rung trends, pipeline representation, and parity projections, are real numbers from the 2024 and 2025 *Women in the Workplace* reports by McKinsey and LeanIn.Org. I did not make these up.

The platform metrics, like retention curves and Circle health, are simulated. I used realistic models to generate them, anchored to known baselines. For example:
- Promotion lift is based on Lean In’s roughly 2× claim
- Retention follows a realistic drop-off curve
- Circle health reflects plausible engagement patterns

Everything is labeled clearly so it’s easy to see what’s real and what’s simulated.

## Tools I used

- **Chart.js** for all the visualizations
- **Plain HTML, CSS, and JavaScript**, no frameworks
- I used a simple AI tool only occasionally for brainstorming ideas or small tweaks, but all the design, coding, and analysis decisions were mine

## What I’d do differently with more time

I would build a predictive churn model. The retention curve shows a steep drop in the first thirty days, and right now we only see it after members leave. A simple model using early engagement signals could give the team a heads-up and allow outreach before people drop off.

I would also dig deeper into the promotion lift. The 1.87× number is meaningful, but it’s correlation, not causation. Women who join Circles may already be more motivated to advance. A matched cohort study could either validate that figure or spark a more nuanced conversation about what Lean In can truly claim.

## One thing I really want you to notice

The **WoC participation rate** is front and center. I put it there deliberately. If that number is low, it means the platform is mostly helping women who already have advantages—which is exactly the opposite of Lean In’s mission. I want this KPI to be the first thing a leader sees every week, not buried in a filter somewhere.
