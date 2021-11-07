# inconsistent-company-names-demo
Exercise to test Fuzzy Magic in Google Cloud with Cloud Dataprep by Trifacta. The goal is to standardise the company names in a file (VANILLA Ltd, +++ VANILLA LTD +++, vanilla ltd, vanila ltd, Vanilla Ltd., etc.) before uploading them to the target table in BigQuery.

You have the step-by-step instructions in "Inconsistent company names demo.pdf" to repeat the exercise.

Data to run the demo: companies.csv.

After doing the demo myself, I saved:
* The recipe companies.wrangle with the data preparation steps I took.
* The flow VanillaFlow.zip to ingest the data from the file into BigQuery.


Fuzzy Matching or approximate string matching --> https://celiamuriel.blogspot.com/2021/11/fuzzy-matching-or-approximate-string.html
Fuzzy Matching Demo: Inconsistent company names --> https://celiamuriel.blogspot.com/2021/11/fuzzy-matching-demo-inconsistent.html
