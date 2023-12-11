# ChildhoodCancerDataInitiative-CCDI_IndexeRy
This script will take a [CCDI metadata manifest file](https://github.com/CBIIT/ccdi-model/tree/main/metadata-manifest) and converts to a CDS-like Indexing template, for DCF and CGC, based on a fixed set of property equivalencies.

Run the following command in a terminal where python is installed for help.

```
python CCDI_IndexeRy.py -h
```

```
usage: CCDI_IndexeRy.py [-h] -f FILENAME

This script will take a CCDI metadata manifest file and converts to a CDS-like Indexing template based on a fixed set of property equivalencies.

required arguments:
  -f FILENAME, --filename FILENAME
                        CCDI dataset file (.xlsx)
```
