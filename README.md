# cissig
The public repository including all code to recreate the analysis and figures from, "Exploiting convergent evolution to derive a pan-cancer cisplatin sensitivity gene expression signature."

In order to extract cissig, the following files should be run in order:

1. `download_data.Rmd`
2. `clean_data.Rmd`
3. `extract_cissig.Rmd`

From there, the specific order of scripts does not matter. `model_sig_gdsc.Rmd` should be run to perform predictive modeling within the GDSC dataset (where the signature was extracted from). `plot_sig.Rmd` can be used to visualize results.