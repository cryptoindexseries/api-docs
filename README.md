# CryptoIndexSeries Api

After exporting API definition from AWS API Gateway following changes should be made manually; 

- Copy content of docs/additonal.md to info > description of yml file. (See old commits If this seems vague)
- Prepend /trading to /cis-trading paths, open an text editor (e.g. Sublime Text) and use Find and Replace (e.g. find /cis-trading and replace with /trading/cis-trading)
- Prepend /portfolio to /cis-portfolio paths (same logic as above)
