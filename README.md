# RiskCalculator

This Risk Calculator is based on a modified version of CVSS v3.

CVSS v3 formulas are used. I made the decision to leave out Remediation Level and Modified Environmental scores. Additionally, I changed the risk levels to High, Moderate, and Low. High is >7, Moderate is 6.9 - 4.0 and Low is < 4.0.

I also added an Expected Risk category. The purpose of this is to keep track of expected risks versus identified risks. Items which fall into the expected risk category are as follows:

"Story Written" - This identifies a risk which is anticipated and a story has already been written for the risk.
"Accepted" - This pertains to risks which are identified during and assessment which has already been accepted.
"Environmental" - This is a risk that exists outside of the developers code-basse or outside of areas the develpment team can control.

The Spreadhseet calculates the Total Risk, Expected risk, and the number opf High, Moderate and Low vulnerabilities. There is also a macro which sorts risks based on the score.

If you have any suggestions for improvements, please let me know.
