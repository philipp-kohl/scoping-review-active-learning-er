# Scoping Review of Active Learning Strategies and their Evaluation Environments for Entity Recognition Tasks


This repository hosts supplementary materials for the paper titled [Scoping Review of Active Learning Strategies and their Evaluation Environments for Entity Recognition Tasks](https://doi.org/10.1007/978-3-031-66694-0_6).
Given the extensive data generated from a scoping review, we have provided the supplementary material in TSV format. This enables users to analyze the data using their preferred tools:
- Corpora: [Corpora Table](datasets.tsv)
- Screening: [Screening Table](screening.tsv)
- Strategies: [Strategies Table](strategies.tsv)

For access to the datasets mentioned in our study, please visit [NER Datasets](https://github.com/philipp-kohl/ner-datasets).

## Further Information for the Screening Process

*Combination* is composed of the following exclusion reasons:
- semi supervised learning
- reinforcement learning
- weak supervision
- self learning
- pre-tagging
- distant supervision
- adversial
- self training
- proactive learning
- data-augmentation
- over-labeling
- imitation learning

*Other* is composed of the following exclusion reasons:
- not-reproducible
- AL strategy uses ML
- feature AL
- Explainable AL

## Citation
If you find this repository useful in your research, please cite:

```
@inproceedings{kohl_scoping_2024-1,
  title = {Scoping {{Review}} of~{{Active Learning Strategies}} and~{{Their Evaluation Environments}} for~{{Entity Recognition Tasks}}},
  booktitle = {Deep {{Learning Theory}} and {{Applications}}},
  author = {Kohl, Philipp and Kr{\"a}mer, Yoka and Fohry, Claudia and Kraft, Bodo},
  editor = {Fred, Ana and Hadjali, Allel and Gusikhin, Oleg and Sansone, Carlo},
  year = {2024},
  pages = {84--106},
  publisher = {Springer Nature Switzerland},
  address = {Cham},
  doi = {10.1007/978-3-031-66694-0_6},
  abstract = {We conducted a scoping review for active learning in the domain of natural language processing (NLP), which we summarize in accordance with the PRISMA-ScR guidelines as follows:},
  isbn = {978-3-031-66694-0},
  langid = {english}
}
