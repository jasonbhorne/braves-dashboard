# Braves True-Talent Dashboard

A self-updating analytics dashboard for the Atlanta Braves: is each player's
performance real or luck?

Live page: https://jasonbhorne.github.io/braves-dashboard/

## What it shows

- Team trend: rolling 15-game win pct, runs scored vs allowed, and expected
  wOBA for the offense and pitching staff
- Every hitter and pitcher over Season / Last 30 day windows, comparing actual
  wOBA to expected wOBA (xwOBA) from Statcast contact quality
- An auto-flagged watch list: fading players, lucky streaks due for
  regression, fastball velocity drops, and vanishing whiff rates

## Data

MLB Stats API and Baseball Savant pitch-level Statcast data, regular season
games only. Rebuilt on demand; the build date is stamped in the page header.

Built with Claude Code.
