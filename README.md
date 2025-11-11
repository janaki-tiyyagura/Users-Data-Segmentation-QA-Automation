# Users-Data-Segmentation-QA-Automation
" A Graphical User Interface tool helps us perform segment QA more efficiently, check attribute values and save time and effort. "


"Develop an automated script that extracts details from Braze using the unique segment API and generates an output file listing each attribute and its values line by line. The result should indicate whether all selected inputs in Braze are correct or not. Additionally, the utility should check for any values with leading or trailing spaces or inconsistent letter casing and reflect these findings in the output file which help to identify the error.
"

Problem Categories
 1. Data Quality Issues - Manually entered values may contain leading/trailing spaces and inconsistent casing (e.g., “Value” vs “value” vs “ value ”).
2. Hard-to-Detect Errors - These formatting inconsistencies are not easily visible, making them difficult to catch during reviews or quality checks.
3. Incorrect Final Counts - Minor discrepancies in formatting can lead to incorrect matching, aggregations, or filtering which impact the segment count and final outputs.
4. Data Mismatches - Misaligned values may not match the expected standards, causing logic failures or misclassification.

Opportunity Areas
Standardizing Inputs: Comparing manually entered values against a predefined list of standard (hardcoded) values to detect discrepancies.

