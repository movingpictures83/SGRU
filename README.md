# SGRU
# Language: Python
# Input: TXT
# Output: PREFIX
# Tested with: PluMA 1.1, Python 3.6

PluMA plugin that runs Staged Gated Recurrent Unit (Cho et al, 2014).

The plugin expectes as input a tab-delimited file of keyword-value pairs:
inputfile
hours
features
K
stagefile
nonstagefile
units
lr
epochs
slice

Output CSV files for predictions (Y and Yhat) are produced using the user-specified prefix.
