# mhcflow reference set

## Class I (hg19)

The reference set for class I is the same as provided in the original `polysolver`
algorithm.

- `abc_complete.fasta`: class I genomic reference provided to `--ref` option.
- `abc_v14.uniq`: 38mer class I tag sequences provided to `--tag` option.
- `HLA_FREQ.txt`: population frequency of class I alleles at 4D resolution
provided to `--freq` option.
- `hla.bed`: genomic intervals for class I genes provided to `--bed` option.
    - Note: change this file accordingly if you have difference chromosome
    naming.

## Class II (hg19)
- `class2.ref.fasta`: class II genomic reference provided to `--ref` option.
- `class2.ref.38mer.tag`: 38mer class II tag sequences provided to `--tag` option.
- `class2.ref.supertype.freq.tsv`: provided to `--freq` option.
    - Note: this file does not provide population frequency for class II. It is
    primarily used for filtering out alleles that you do not want to type.
- `class2.bed`: genomic intervals for class II genes provided to `--bed` option.
