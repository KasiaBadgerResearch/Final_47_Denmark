# How has the share of women with tertiary education evolved relative to that of the overall population in Denmark between 1960 and 2010?

## Abstract

Using World Bank World Development Indicators (WDI) data, this study examines the evolution of tertiary education attainment in Denmark between 1960 and 2010, comparing the female population aged 25+ with tertiary schooling to the overall population aged 25+ with tertiary schooling. The analysis captures long-term trends in educational expansion, gender parity, and societal investment in human capital. From 1960 to 1985, the proportion of women with tertiary education was roughly half that of the total population, reflecting historical gender gaps in access to higher education. After 1990, female attainment increased substantially, approaching parity with the overall population, while both indicators rose significantly over the period. By 2010, the female and total shares had almost converged, highlighting Denmark’s success in promoting gender equality in higher education and illustrating broader structural shifts in access to knowledge, labour market preparedness, and socio-economic development.

## 1. Question

How has the share of women with tertiary education evolved relative to that of the overall population in Denmark between 1960 and 2010?

- **Female tertiary education proxy**: Percentage of female population age 25+ with completed tertiary schooling (WDI, based on Barro-Lee estimates)
- **Total tertiary education proxy**: Percentage of population age 25+ with completed tertiary schooling (WDI, based on Barro-Lee estimates)

## 2. Data

- **Source**: World Bank World Development Indicators (WDI)
- **Indicators**:
  - Female population aged 25+ with completed tertiary schooling (%)
  - Total population aged 25+ with completed tertiary schooling (%)
- **Coverage**: Denmark, 1960–2010
- **Notes**: National-level data only

## 3. Method

1. Filtered dataset for Denmark and selected the two tertiary education indicators.
2. **Extracted relevant columns**: Year, Indicator Name, and Value.
3. Pivoted the dataset to create a side-by-side chronological comparison of female versus total tertiary education shares.
4. Produced a dual-line time series plot to visualise long-term trends, convergence, and relative gaps between female and total tertiary education attainment.

(Analysis is descriptive; no causal inference applied.)

## 4. Results

- **Female tertiary education (%)**: Increased steadily from 1960 onwards, with a marked acceleration after 1990, approaching parity with total tertiary attainment by 2010.
- **Total tertiary education (%)**: Grew significantly over the entire period, consistently higher than female shares until the early 2000s, before almost converging by 2010.
- **Comparison**: In the early decades, female attainment was roughly half of total tertiary levels, but over time both indicators increased substantially, with female shares catching up to the total population. The near-convergence by 2010 signals strong progress towards gender equality in higher education access in Denmark.

(Figure 1. Denmark: Female vs. Total Tertiary Education, 1960–2010)

(Table 1. Pivoted dataset summary)

## 5. Interpretation

- The persistent gap in earlier decades reflects historical gender inequalities in access to higher education and labour market expectations.
- The rapid growth in female tertiary attainment after 1990 indicates the effectiveness of policies promoting gender equality, educational access, and societal investment in women’s human capital.
- The convergence of female and total tertiary attainment by 2010 demonstrates a structural shift in Denmark’s education system, reflecting changing social norms and targeted policy interventions.
- Understanding these trends is crucial for anticipating labour market participation, wage equality, and economic productivity, as higher education strongly correlates with workforce outcomes.

## 6. Limitations

- National aggregates may obscure regional or field-specific differences in tertiary attainment.
- WDI estimates, while based on Barro-Lee data, carry uncertainty, particularly for earlier years.
- The analysis is descriptive and does not isolate causal factors such as educational reforms, demographic shifts, or cultural changes influencing female participation.

## 7. Next Steps / Extensions

- Disaggregate tertiary attainment by field of study to examine gender parity in STEM versus humanities.
- Analyse correlations between tertiary education shares and female labour force participation, wage gaps, and occupational outcomes.
- Compare Denmark’s gender convergence trends with other Nordic or European countries to contextualise regional progress.
- Conduct time-series decomposition to separate structural improvements in education access from short-term fluctuations or cohort effects.
