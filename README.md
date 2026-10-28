# Kingston Hogsmill Monitoring Data Explorer

A beginner Python project exploring Environment Agency river-level
data and rainfall-data availability near Kingston Hogsmill.

## Completed work
- Identified the Kingston Hogsmill river-level station.
- Downloaded a one-week sample of 15-minute river-level readings.
- Checked timestamps, missing values, duplicates and quality flags.
- Plotted recorded river levels over time.
- Investigated rainfall data from Hogsmill and Putney Heath.

## Rainfall findings
The tested Hogsmill rainfall samples contained no readings that
were both Complete and Good under the project's filtering rule.

Putney Heath returned no readings for the requested October week.

Rainfall comparison is therefore not included in this version.

## Tools
- Python
- requests
- pandas
- Matplotlib
- Google Colab

## How to run
Open flood_analysis.ipynb in Google Colab and run the code cells
from top to bottom. Internet access is needed for API requests.

## Data source
Environment Agency Hydrology API:
https://environment.data.gov.uk/hydrology/doc/reference

The notebook records station identifiers and requested dates.
Results may change if the source data are revised.

## Limitations
This is exploratory monitoring-data analysis, not a flood
prediction system or a complete Digital Twin.

Recorded river level is not flood depth. The analysis does not
establish whether flooding occurred or assess infrastructure safety.

## Next improvements
- Investigate rainfall completeness flags and station coverage.
- Review river-level quality flags in more detail.
- Add a rainfall comparison only when suitable data are available.

## Learning context
Built as a guided learning project to develop Python,
environmental-data analysis and documentation skills.
