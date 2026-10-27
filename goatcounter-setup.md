# Visit log + "who opened it" (GoatCounter, free, ~3 minutes)

## 1. Turn on the log
1. Sign up at https://www.goatcounter.com/signup and pick a code, e.g. `dhruvsadhwani`. Your dashboard is then `https://dhruvsadhwani.goatcounter.com`.
2. In `index.html`, set `goatcounter: ""` in the DATA block to your code, e.g. `goatcounter: "dhruvsadhwani"`. Commit and push.
3. Open your live site once with `#me` at the end (https://sadhwanidhruv.github.io/Portfolio/#me) so your own visits are not counted.

The dashboard then shows every visit: time, country, device, browser, screen size and where each visitor came from.

## 2. Know who opened it: labelled links
Add `?ref=<label>` to the link you send each person. Use a different label per person or place:

- https://sadhwanidhruv.github.io/Portfolio/?ref=recruiter-priya
- https://sadhwanidhruv.github.io/Portfolio/?ref=prof-rao
- https://sadhwanidhruv.github.io/Portfolio/?ref=linkedin
- https://sadhwanidhruv.github.io/Portfolio/?ref=whatsapp-group

In the dashboard open **Referrers** (the "Top referrers" panel). Each label appears with its visit count, so you can see who opened your link. Visits that come from a labelled link are only as accurate as the link: if someone forwards it, the label travels with it.

Notes: some ad blockers block GoatCounter, so those visitors are missed. The visible "N visits" badge on the site is separate and keeps working without GoatCounter.
