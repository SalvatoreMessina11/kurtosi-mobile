# Rolling kurtosis and market fragility

An exploratory Python notebook for studying the rolling kurtosis of weekly log returns as a descriptive measure of changes in the shape of return distributions.

## Research question

Can rolling estimates of tail heaviness help describe periods of unusual market behaviour? This notebook examines that question with a time-series view of kurtosis. Kurtosis is a descriptive statistic; by itself it does not establish a tradable signal or forecast a market event.

## Notebook

Open [Kurtosi_mobile.ipynb](Kurtosi_mobile.ipynb) to inspect the data processing, calculations, and visual analysis.

## Interpretation

Rolling statistics depend on the sample window and the quality of the input data. Short windows can produce noisy estimates, while extreme observations can dominate kurtosis. Treat the charts as exploratory diagnostics and verify any inference against additional evidence.

This is an educational research project, not investment advice.
