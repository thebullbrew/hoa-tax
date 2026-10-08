# The HOA Tax

![The HOA Tax preview](assets/preview.png)

![The HOA Tax banner](assets/banner.jpg)

**Live app:** https://thebullbrew.github.io/hoa-tax/

## What it does

HOA dues look small per month. Over a hold, they become a *second mortgage you never applied for* — escalating every year, punctuated by five-figure special assessments. The HOA Tax adds it all up into one honest number:

- **Total dues paid** over your holding period, with the board's annual increase baked in
- **Special assessment** (optional, lands in the year you say it will)
- **The real tax**: dues grown at your opportunity rate — what those dollars *would have become* if a committee weren't spending them
- **Burn rate**: the daily cost of ownership just from dues
- **The escalation trap table**: same dues, different boards — lifetime dues across escalation rates (0–8%/yr) and hold lengths (5–30 yrs), before assessments or lost growth
- **Deal survival check** (Investor tab): dues as a share of rent, cash flow before/after HOA, and 10 years of cash flow lost to dues — with a plain-spoken verdict
- **Saved scenarios** (browser-local), **copy summary**, buyer/investor modes

## The method behind it

Dues compound monthly off your escalation rate; opportunity cost compounds annually on every dollar paid — that's the honest "real tax," because money spent on dues is money not compounding somewhere else. Special assessments carry opportunity cost from the year they land.

Verdict bands: under 10% of the purchase price over the hold is a toll worth grumbling about; 10–20% is a second mortgage you never applied for; over 20% and you didn't buy a home — you bought a subscription. Investors get the same math as a share of rent: over 20% and the HOA is your equity partner, and you never agreed.

And the standing filter: *if the numbers only work because you pretend the dues won't rise, they don't work.* Ask the board for five years of dues history before you buy — boards raise dues like landlords raise rent, except you can't move out of the board.

## Run it

No build step, no backend, everything client-side.

```bash
cd docs
python3 -m http.server 8080   # or just open index.html directly — it works from file://
```

Then visit http://localhost:8080. Installs as a PWA (offline-capable) from any static host.

---
Built by [The Bull Brew](https://github.com/thebullbrew) — one useful tool, every day.
