## plot_structure

Interative plot generation for FastStructure

## Requirements

Python3 is required. The necessary lib dependencies are list in the requirements.txt file.

```
pip install -r requirements.txt
```

## Usage

```
plot_structure.py -in <faststructure_meanQ_file> -o output_name -p taxa_list_file
```

The taxa_list_file should be a simple text file with the name of each taxon in the meanQ file per line. Example:

```
TaxonA
TaxonB
TaxonC
.
.
.
```

## Example

<img src="https://github.com/ODiogoSilva/interactive_structure/raw/master/demo.gif">
