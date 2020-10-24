# nmt_v3

third nmt system this time in pytorch


### Usage

**Data**

The data should be pre-tokenized. It should live in two-column `src \t tgt` tsv files.

**Train a model**

`python seq2seq.py --train /path/to/train/data.tsv --test /path/to/test/data.tsv --working_dir your_wd/`


**Test a model**
TODO -- make train data optional
`python seq2seq.py --test /path/to/test/data.tsv --checkpoint your_wd/model.ckpt`
