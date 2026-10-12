# Fiscal Recovery Funds in America's Metropolitan Cities

An interactive look at how much the 770 U.S. metropolitan cities with more than 50,000 residents received from the American Rescue Plan's State and Local Fiscal Recovery Funds, how fast they spent it, what they spent it on, and how homicide, violent crime, and property crime moved.

The site is static: `index.html` holds the city summaries, and `data/projects/` holds each state's project-level detail, loaded on demand.

## Sources

- Allocations and projects: U.S. Department of the Treasury, SLFRF Project and Expenditure Report public data, releases with data through December 2021 and June 2022 to March 2025.
- City budgets: U.S. Census Bureau, 2017 Census of Governments.
- Population: American Community Survey 2015 to 2019.
- Crime: Real-Time Crime Index (AH Datalytics), with the FBI Uniform Crime Reports (Kaplan, 2025) as a backup where the index has no data.

## Hosting

Served with GitHub Pages from the root of the `main` branch. The empty `.nojekyll` file tells Pages to serve the files as they are.
