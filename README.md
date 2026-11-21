# Lake-Mendota-Clarity-and-Zooplankton-Analysis
Exploratory analysis and visualization of water clarity and zooplankton population trends in Lake Mendota using Pandas, Matplotlib, and Statsmodels.

## Key Findings
* **Finding 1:** The spiny water flea experienced in increase in its annual mean population density from 2009-2014, as shown by the positive OLS regression coefficient of 51.2. This corresponds to an increase of 51.2 organisms/m² per year. From 2015-2024, the annual mean population densities yielded a negative linear relationship with a coefficient of -6.5758 that indicates a decrease of ~6.58 organisms/m² per year.
* **Finding 2:** A long-term decrease in Lake Mendota's average summer water clarity was identified. An OLS regression coefficient of -0.0373 revealed we lost about 0.0373 meters of clarity annually from 1995-2004.
* **Finding 3:** Lake Mendota's average summer clarity became more variable after 2015, coinciding with a decrease in the mean density of the spiny water flea population, although this does not prove causation.
  
## Data Sourcing
The datasets used in this analysis were sourced from the [Environmental Data Initiative (EDI) Data Portal](https://portal.edirepository.org)
* **Dataset Title:** North Temperate Lakes LTER: Secchi Disk Depth; Other Auxiliary Base Crew Sample Data 1981 - current
* **Package ID:** knb-lter-ntl.31.34
* **Dataset Title:** North Temperate Lakes LTER: Zooplankton - Madison Lakes Area 1997 - current
* **Package ID:** knb-lter-ntl.90.37
* **Access Note:** Raw data files are excluded from this repository per portal access guidelines. To reproduce the notebook, create a free account on EDI, download the packages above, and place the CSV files in a local `data/` directory.
To run locally, download and unzip these two North Temperate Lakes LTER packages from EDI into a `data/` folder:
* `knb-lter-ntl.31.34` (Zooplankton)
* `knb-lter-ntl.90.37` (Water clarity)
