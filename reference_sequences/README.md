# Making reference sequence databases
The Xander paper (Wang et al., 2015) used the following ref seq for these genes

| Protein | # seq | min aa | min HMM coverage (%) | min HMM score | avg lenth (aa) |
| --------- | ----- | ---------- | --------- | -------- | :-----: |
| RplB | 1734 | 250 | 90 | 440 | 280 |
| NirK | 263 | 300 | 80 | 300 | 410 |
| NifH | 782 | na | na | na | 300 |

Sequence counts used should mirror the above with diverse phylogenetic markers containing more sequences than functional genes of interest. 

# Steps
1. Downloaded sequences from FunGene based on [set parameters](https://github.com/ShadeLab/ARG-AsRG_co-occurrence_Centralia/blob/master/reference_sequences/FunGene_references.md)
2. Compile references using the following code: [compiling_references.md](https://github.com/ShadeLab/ARG-AsRG_co-occurrence_Centralia/blob/master/reference_sequences/compiling_references.md)
