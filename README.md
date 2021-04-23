# About

RapidMiner examples and POCs.



## python environments

I use conda and created an environment called `rapidminer`.  This repo contains the conda environment as well as the results of `pip freeze`.

After you have your environment setup, you will need to run the following command (with your `rapidminer` environment activated).

```
python -m spacy download en_core_web_md
```

Finally, ensure that you have configured RapidMiner to use your `rapidminer` environment by default.  This can be found via RapidMiner > Preferences > Python.


## TODO

- faker example, perhaps to GCP, and then GCP to SFDC
- wikipedia crawl for text mining with spacy






