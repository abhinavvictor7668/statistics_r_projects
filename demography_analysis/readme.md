demography_analysis
- Purpose: Explore relationships and trends in demographic and development indicators across countries/time. Typical analysis steps present in the project:
	- Data ingestion and cleaning of CSVs containing fertility, expenditure, birth and internet-related indicators.
	- Descriptive statistics and distributions for core demographic variables (e.g., fertility rates, birth rates).
	- Comparative analysis (for example, fertility vs. education/expenditure across years such as 1960 vs 2013).
	- Simple bivariate analyses and scatterplots to inspect associations (e.g., Fertility vs Expenditure, Births vs Internet access).
	- Tabular summaries and highlighted observations reported in the R Markdown document and exported PDF.

Files to note:
- `Demography Analysis.Rmd` — primary analysis notebook containing narrative, code, figures and summary interpretation.
- `Demography-Analysis.pdf` — rendered output of the R Markdown (print-friendly report of the analysis and figures).
- `Fert vs Exp 1960.csv`, `Fert vs Exp 2013.csv` — datasets comparing fertility and expenditure in the specified years.
- `Birth vs Internet.csv` and `S5-Demographic-Data.csv` — supporting datasets used in visualizations and tables.
