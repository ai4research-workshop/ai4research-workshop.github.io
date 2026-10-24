# AI4Research

Website for the Workshop on AI for Scientific Research at AAAI.

- `/` — 2027, second edition, Montréal, Canada.
- `/2026/` — complete first-edition archive, Singapore, January 26, 2026.

## Local preview

Run `python3 -m http.server 8000` from the repository root and open
`http://localhost:8000/`. The site is static HTML, CSS, and JavaScript.

## Maintaining the site

- Edit `index.html` for 2027. Both editions use the original TheEvent template
  and shared `assets/css/style.css` and `assets/js/main.js`.
- The 2026 archive retains its original content. Its paper data lives
  in `2026/accepted_papers.csv`. Slides and maps retain their locations under
  `assets/` so existing resource URLs remain usable.
- Confirm the workshop day before replacing the date placeholder. February
  22–23 is the overall AAAI workshop program, not a two-day AI4Research schedule.
- The 2027 submission deadline is November 20, 2026, 23:59 AoE; notifications
  are December 2, 2026. The [OpenReview venue request](https://openreview.net/forum?id=uKUss0nIMM)
  was submitted for `AAAI.org/2027/Workshop/AI4Research`. Link the submission
  portal after OpenReview approves and deploys it, then change “Opening soon”.
- Add speakers, the detailed program, accepted papers, and awards as available.
  Keep each year's content separate when adding future editions.

Contact: hui.chen@nus.edu.sg or yilun.zhao@yale.edu.
