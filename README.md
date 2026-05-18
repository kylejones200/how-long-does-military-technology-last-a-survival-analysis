# How Long Does Military Technology Last A Survival Analysis

Published: 2025-05-21
Medium: [https://medium.com/@kyle-t-jones/how-long-does-military-technology-last-a-survival-analysis-025308994cd0](https://medium.com/@kyle-t-jones/how-long-does-military-technology-last-a-survival-analysis-025308994cd0)

## Business context

I wondered how long military technologies remain deployed. I used the [Correlates of War Arms Technology Dataset](https://correlatesofwar.org/data-sets/arms-technology-data-v1-0/), which provides a global, historical record of military technology usage from 1816 to 2023. It doesn't tell you whether a weapon is effective. It tells you whether it's still part of a country's active arsenal in a given year.

Each row in the dataset represents a country-year-technology observation. For example, the United States might be listed as using the M16 assault rifle from 1964 through 2023. Each of those years appears as a separate row with a field labeled use.

I limited our analysis to rows where use == 1. This ensures we're only measuring active, meaningful deployment --- not prototypes, tests, or weapons that have been leapfrogged by more advanced systems.

## About

Place the code for this article in this repository.
The original article export is saved as `article.md`.

## Files

Add your `.ipynb`, `.py`, `.yaml`, `.js`, `.ts`, or other project files here.

## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).