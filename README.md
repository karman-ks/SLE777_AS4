# SLE777_AS4
This respoitory contains the R Markdown file containing the code for assessment 4 for SLE777 and the resulting HTML file when it is knitted. 

**Part 1, questions 1-5** involves the gene_expression.tsv dataset which includes information about the expression of certain genes within three different samples. The file was first read in, the mean expression of all genes was calculated and the gene expression was visualised with a historgram. 

**Part 1, questions 7-10** read in the growth_data.csv dataset which contains the measurements of tree circumference at two different sites from 2005 to 2020. The mean and standard deviation of the tree circumferences were calculated, the distribution of the dataset was visualised using a boxplot, the mean 10 year growth in tree circumference was then calculated, and a t-test was conducted to test whether the 10 year growth rate was statistically significantly different at one site from the other. 

**Part 2** involved the comparison of the total coding sequences of *E.coli* to *S.thermophilus*. The following parameters were computed:
- Number of coding sequences
- Number of total base pairs within the total coding sequence
- Frequency of nucleotides within the total coding DNA sequence
- Frequency of amino acids within the total coding DNA sequence, after translation
- Codon usage table, with a focus on Relative Synonymous Codon Usage (RSCU) values
- Top 10 under- and over-represented k-mers of length 3-5

The **session info** is present at the end of the R-markdown HTML file, along with the **references** used for this assessment. 

**Packages used for this assessment**

seqinr 


R.utils
