# One Lane Brain

A three-minute phone game that measures your brain's decision bottleneck.

- **Left box** turns blue or orange. Tap the matching color with your left thumb.
- **Right box** shows an arrow, up or down. Tap the matching arrow with your right thumb.
- When both appear, answer the left box first, then the right.

Part 1 times the right box alone, so you have a baseline. Part 2 shows both boxes, with the right one appearing 50 to 1,000 ms after the left.

## What it shows

When the right box comes long after the left, you answer at normal speed. When it comes almost at once, the right decision has to wait until the left one finishes. The shorter the gap, the slower the second answer.

- **Wait at the shortest gap**: extra time on the right box at a 50 ms gap vs a 1,000 ms gap.
- **Slope**: extra wait for each 100 ms sooner the right box appears. Close to 100 means strictly one decision at a time.
- **Chart** of both answers by gap, against your baseline.
- **History** of your last 20 runs, saved in your browser only.

Times use the median (the middle value) of correct trials, so one slow tap doesn't skew them.

## Limits

30 trials is a small sample. Phone screens and touch add a few hundredths of a second of noise. Lab studies use hundreds of trials and special equipment.

## Background

The psychological refractory period: Telford (1931); Welford (1952); Pashler (1994); Dux et al. (2006); Ruthruff et al. (2003); Levy, Pashler and Boer (2006).

## Run it

Open `index.html` in any browser, or turn on GitHub Pages for this repo (Settings > Pages > Deploy from branch > main).
