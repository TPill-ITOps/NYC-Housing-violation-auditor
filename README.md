# NYC-Housing-violation-auditor
# NYC Housing Violation Auditor (NYChunt)

## Strategic Purpose
This tool was developed to perform technical due diligence on New York City residential properties. By pulling raw data directly from the NYC Open Data API, it allows an analyst to bypass consumer-facing marketing sites and assess the true "maintenance debt" of a building.

## Technical Problem Solved
* **Infrastructure Independence:** Built using native Python `urllib` to ensure execution on standard Linux environments without third-party dependencies.
* **Data Sanitization:** Implements logic to normalize street suffixes to match strict government database requirements.
* **Efficient Auditing:** Reduces a manual search process to a <10-second automated CLI audit.

## Tech Stack
* **Language:** Python 3
* **OS:** Ubuntu Linux (CLI)
* **API:** Socrata Open Data (NYC HPD Maintenance Code Violations)

## How to Run
1. Run the script: `python3 iNYChunt.py`
2. Enter building number and street name when prompted.
