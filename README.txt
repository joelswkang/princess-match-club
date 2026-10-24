Princess Math Club — v1.7

This update keeps the existing v1.5-style layout and v1.6 capsule/collection system while adding daily limits, daily challenges, a stamp shop, learning feedback, and app credit.

What's included
- Main screen version label: Version 1.7
- Developer credit: Developed by Joel Kang
- Mobile pinch-to-zoom disabled
- Daily Adventure: maximum 100 questions per child per New Zealand calendar day
- Daily Challenge: one attempt per child per New Zealand calendar day; challenge questions count toward the 100-question daily allowance
- Questions are answered interactively. Adventure mode gives immediate feedback and a short strategy hint; the Daily Challenge hides right/wrong feedback until the end
- Challenge completion earns one spendable stamp even when the score is below 100%; a perfect score earns one bonus capsule
- Every 20 completed Daily Adventure questions earns one spendable stamp
- Stamp Shop: choose accessories, outfits, and magical backdrops
- Existing capsule inventory, princess collection, accessories, monthly records, and settings are preserved
- Daily usage and rewards are stored locally and separately for Leah and Lena
- No cloud sync; data stays in this browser/device

Validation performed
- JavaScript syntax check passed
- 16 automated logic checks passed, covering the daily question cap, reduced remaining allowance, one challenge per day, perfect/non-perfect challenge rewards, stamp purchases, per-child separation, hidden challenge answers, and New Zealand day reset
- This is not a physical iPhone/Safari test. Please test the deployed build on the existing site before relying on it.

Deploy safely
1. Back up the current repository files first.
2. Unzip this package.
3. In the SAME existing GitHub Pages repository, replace the root index.html and manifest.json with these files (keep the existing repository and URL).
4. Do not clear Safari website data or localStorage. Existing progress uses the current pmc-data and pmc-rewards-v1-* keys; this update keeps those keys.
5. Test both children on the deployed URL. Daily limits are per child and use the New Zealand calendar date.
