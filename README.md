# Pakistan Sales Performance Tracker

A macro-enabled Excel workbook that tracks a five-day sales push across 70 sales executives spread over 15 Pakistani cities, and turns the raw numbers into pivot tables, charts, and a region slicer you can click through.

## What this is

Every sales executive on the team was given a target of 500 units to hit over five working days. This workbook logs what each of them actually sold, day by day, and then does the math for you — total sales, percentage of target hit, and how far off they landed.

It's built the way a small sales team would actually use it: one flat sheet for entering the daily numbers, and a second sheet that turns those numbers into something a manager can glance at during a Monday meeting.

## What's inside

**Sheet1 — Raw Data**
The working sheet. One row per employee, with:
- Employee code and name
- Region/city (Hyderabad, Lahore, Karachi, Faisalabad, Islamabad, Peshawar, Sialkot, and more)
- Daily sales for Day 1 through Day 5
- Auto-calculated Total Sales, Target Hit %, and Away From Target %

**Sheet2 — Dashboard**
This is where the raw numbers turn into a story:
- Four pivot tables breaking down performance by sales executive, filterable by region
- Charts visualizing totals at a glance
- A region slicer, so you can click "Karachi" or "Lahore" and watch every table and chart filter down instantly

## How to use it

1. Open the file in Excel and enable macros (it's a `.xlsm`, so Excel will ask — say yes, since the workbook uses a bit of VBA under the hood).
2. Enter or update daily sales figures in Sheet1. The Total, Target Hit %, and Away From Target % columns recalculate automatically.
3. Head to Sheet2 to see the pivot tables and charts update, and use the region slicer to zoom into a specific city's performance.

## A few honest notes

- Every executive shares the same 500-unit target — there's no weighting for region size or team headcount, so read the percentages with that in mind.
- The daily sales numbers here are sample data, not figures from a real sales operation.
- The dashboard is meant as a quick pulse-check, not a full analytics suite — it's most useful as a starting point you can extend with more regions, targets, or time periods.

---
Built by Areeba Sattar.
