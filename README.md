# HLA_article

This script takes the input xlsx-file with special formatting like the example Data_covid_for_article.xlsx
Five genes of humal HLA can be presented in double columns of alleles by dictionary like this:
    "A": 1,
    "B": 3,
    "C": 5,
    "DRB1": 7,
    "DQB1": 9

The structure of group import can be linked by name of xlsx-sheets
By the way, the output of this pipeline gives the broad overview of significant alleles and the presence of significant differences between groups, for example between covid severity groups
Several chunks are devoted to obtaining a suitable data format for use as an input to the Arlequin program.
Also, it creates pictures illustrating the comparative population of groups, the profile of the proportion of alleles for each group, the clustering of samples, and so on.
