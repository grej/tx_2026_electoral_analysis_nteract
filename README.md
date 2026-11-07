# Texas early voting: 2026 vs 2024 by precinct

A single notebook that compares Texas's 2026 early in-person turnout with the same point in 2024, precinct by precinct, grouped by how each precinct voted in 2024. 
It is a simulation based forecast of the U.S. Senate and governor races from the polling averages, using the early-vote data to show how much of the polled shift since 2024 comes from who is turning out.

## Open it

1. Install **[nteract](https://nteract.io)**, a free, open-source NumFOCUS project.
2. Open `texas_early_vote_2026_vs_2024.ipynb` and run all cells.

The notebook carries its own **pinned conda environment**, so nteract sets up the exact Python and package versions for you. The early-vote data is embedded in the file, so there's nothing else to download. The one exception is Step 5, which fetches about 83 MB of Texas Legislative Council tables on its first run.

Other Jupyter tools work too if you install the pinned packages yourself. They're listed in the notebook's metadata.

## Notes

- Early-vote data: [Jackson Hannan's early-vote dashboard](https://jacksonahannan.github.io/early-vote-dashboard/). All sources are credited inside the notebook.
- Turnout counts can't show how anyone voted. The forecast's win probabilities come from the polls; the early-vote data explains the shift but doesn't change the odds. Every assumption is written out in Appendix C.
- License: BSD 3-Clause (code and text). The data keeps its sources' terms.

## Also here: Democratic Senate Stars (2026)

`democratic_senate_stars.ipynb` is a short, step-by-step notebook that finds the 2026 Democratic Senate nominees who won their race and also ran at or ahead of the national shift. Swing is each candidate's 2026 margin minus their state's 2024 presidential margin. The national shift is +13.9 points, from the 2026 House popular vote (D+12.4, unofficial) against the 2024 presidential vote (R+1.5). It ends in one chart.

It opens the same way: in nteract, with its own pinned conda environment and the data embedded in the file. The 2026 tallies are as of Nov 6, 2026. Mississippi had not been called by AP then, so Colom, who leads, is marked with an asterisk.
