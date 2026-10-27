# Kingshot Alliance Mobilization: Troop Training & Promotion Calculator

Pick an Alliance Mobilization task (15,000, 30,000 or 120,000 points), then
the TrueGold level, the level to train and the level before promotion for each
troop type. The page shows how many troops to train or promote at each camp.

The "Same levels for all 3 troops" box (on by default) shows one row that sets
all three troops at once. Uncheck it to set each troop on its own row.

## Running it

Live at **https://somebodyelsegaming.github.io/ks-am-troop-training/**

One file, `index.html`, with no build step, no backend and no outside links.
Opening it straight from disk works.

## The math

```
troops per camp = task points ÷ (points of the 3 trained troops
                                 − points of the 3 starting levels, if promoting)
```

The result is rounded up, since you can't train part of a troop. Points per
troop by TrueGold level (TG0–TG10) and troop level (1–11) are in the table at
the bottom of the page.

## Credits

Based on TᗩᗰᗩGO's Alliance Mobilization spreadsheet. Points data from the
[original data sheet](https://docs.google.com/spreadsheets/d/1gWxfVCFR_iaYeUYY9mXurvXIFwqKXPG3qeuJFaSvjRk/edit?usp=sharing).
