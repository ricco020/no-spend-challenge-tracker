# No-spend challenge tracker

Free, single-file no-spend challenge tracker. Write the categories you are pausing and what you usually spend on each in a week, tick each no-spend day, log the slips (amount, category, what and why), and it shows:

- the money the challenge has saved so far, per category: usual weekly spend / 7 x days elapsed, minus the slips logged in that category,
- what it comes to if you hold to the end with no new slip,
- the current streak and the longest streak (a blank past day breaks a streak and is flagged),
- the categories with two slips or more, which need a written rule,
- a CSV export of every day (status, amount, category, note).

Challenge length 7 to 90 days. Use it online: https://ricco020.github.io/no-spend-challenge-tracker/

Checked on 300 random challenges (7 to 90 days, 11 060 days, 1 to 5 categories, slips inside and outside the paused list, today before, inside and after the challenge) against a separate Python implementation: 0 difference on elapsed days, no-spend days, slips, blank days, current and longest streak, money saved and money saved by the end.

Printable version (rules page, 30-day tracker, slip log, end-of-challenge page): https://tidysheets.shop/p/no-spend-challenge-printable

Runs fully in the browser, no tracking, no network calls. MIT licence.
