Scripts I use frequently to do my job: handle genetic data, perform analysis and extract some information. Most of them can be called asking for help to see the usage -h --h -help help --help

maker_structure will create multiple Structure submission files for a range of parameters
Also the file to submit them all

popmap_maker will crate a popmap file that lots of softwares (Stacks, FastStructure..) will ask for. It will consider that the name of your files include the population and the sample name. I recommend to use first fixnumeration.pl if needed

save_signif_loci is a shameful script I did to extract loci with significant pair-wise Fst from the general file

bowtie_maker will generate the submission files for bowtie

extractLogtlike: extract the log likelihood from each K ran in Structure (outdated, it was used in an old Structure Unix pipeline)

str_likelihood: extract the row likelihood values from each Structure run to a table (outdated)


