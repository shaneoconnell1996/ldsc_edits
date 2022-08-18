# ldsc_edits
very simple fix for -log10 pvals which adds a flag to munge_sumstats, `--log10pvals`. When selected it applies the inverse to the -log10 pvalues supplied in the sumstats file 


the main `ldsc.py` file has added a new argument, `--rgdf` which will write genetic correlation results to a csv file. You will need the adjusted sumstats file for this to work which is also included  
