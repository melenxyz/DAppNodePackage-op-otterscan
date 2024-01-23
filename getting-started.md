## Otterscan, a An open-source, fast, local, laptop-friendly Ethereum block explorer.
 
### OP-Erigon settings
When running erigon, make sure to enable the erigon, ots, eth APIs in addition to whatever cli options you are using to start erigon. It should at least look like this `--http.api "eth,erigon,ots,<your-other-apis>"`
This is to be added to the config of your Erigon package under `"EXTRA_OPTS"`
