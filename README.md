# PauseCheck prototype

A clickable prototype of **PauseCheck**, an AI co-pilot from FinLit Ventures. It steps in at one moment: when an investor taps "Stop" on their SIPs. Built for the StepSmart product case (E-Cell IIT Guwahati).

**Get the cash. Keep the SIP.**

## Paths to try

1. **A bill:** Priya needs ₹60,000 this week. The Liquidity Router finds the cheapest cash in her portfolio (₹280 in tax), and all 4 SIPs keep running.
2. **A monthly squeeze:** the router shows the smallest step-down first, then pause, skip and cancel, each with its goal impact.
3. **Market fear:** a context card shows goal impact and how this fall compares with past ones.
4. **SIP Buffer:** a share of each instalment fills a liquid fund until it holds 1–3 months of SIPs, then stops.
5. **Stop anyway:** always one tap, processed within SEBI's 2-working-day window.

## Run it

Open `index.html` in a browser. It is a single file with no build step and no dependencies apart from the Poppins font from Google Fonts.

## Notes

- All amounts are illustrative.
- Tax follows FY27 rules: equity gains on units held over 12 months are tax-free up to ₹1.25 lakh a year; debt fund gains are taxed at the investor's slab (20% assumed).
- Every number comes from a rules engine; the AI only explains. FinLit earns nothing from any option shown.
- Information, not investment advice.
