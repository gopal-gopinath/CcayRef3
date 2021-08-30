# CcayRef3
Addtional Data files from the publication Gopinath et al., 202X on The Reference Genome Assembly of Cyclospora Cayetanensis are provided here for community use. The citation will updated after the publication.
'parameters.tar.gz'  was created using Eimeria necatrix genome annotations as the training dataset for AUGUSTUS predictions. This
can be used for Cyclospora genome annotations on the AUGUSTUS server. Upload this file as the input for the parameters file in the 
prediction server data input form.

Mitochondria and Apicoplast .gff files provides simulated overlapping short fragments for querying a database for SNP finding.
These are based on KP231180 and KX189066 respectively. This can be used to find alleles in Eimeridae and possibly Sarcocistidae 
organellar genomes (the latter is not yet tested). GFF files gives coordinates for the sequences based on the two reference genomes.
An example SNP matrix is given as 'Organellar_genomes_SNP_matrix_Figure6'.csv which was generated when the 101 loci listed in the 
two GFF files were used to query a database of genomes from this study.

