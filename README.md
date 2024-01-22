# PortTokenizer
 This repository has portTok.py program, a tokenizer for Portuguese text using Universal Dependencies (UD) format (CoNLL-U) to store the tokenized sentences.

 # Contents
 The main files in this repository are:
- `README.md` - this read explanatory file;
- `portTok.py` - the Python 3 program;
- `sents.txt` - the input file to be used as example;
- `sents.conllu` - the output file generated reading the example input file.

As this program uses a Portuguese lexikon (PortLexicon-UD), this lexikon files are included here, namely:
- `lexikon.py` - a Python 3 package file with the `class UDlexPT`, plus the data files:
   - `ADJ.tsv`
   - `ADP.tsv`
   - `ADV.tsv`
   - `AUX.tsv`
   - `CCONJ.tsv`
   - `DET.tsv`
   - `INTJ.tsv`
   - `NOUN.tsv`
   - `NUM.tsv`
   - `PRON.tsv`
   - `SCONJ.tsv`
   - `VERB.tsv`
   - `WORDmaster.txt`

# Acknowledgments
This work was carried out at the Center for Artificial Intelligence of the University of São Paulo (C4AI - [http://c4ai.inova.usp.br/](http://c4ai.inova.usp.br/)), with support by the São Paulo Research Foundation (FAPESP grant #2019/07665-4) and by the IBM Corporation. The project was also supported by the Ministry of Science, Technology and Innovation, with resources of Law N. 8.248, of October 23, 1991, within the scope of PPI-SOFTEX, coordinated by Softex and published as Residence in TIC 13, DOU 01245.010222/2022-44.

