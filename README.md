# Transcriptional-Stress
This repositroy is for transcriptional stress study including the code (custom and public) and processing data with instruction.<br />

Each code and their corresponding outcome can be found in folder followed by the paper stucture. The extra inputs required from the custome code and public software can be found in the "reference folder" with the following description:

Data processing: <br />
Fastqc QC and alignment <br />
Fastqc See more https://github.com/s-andrews/FastQC.<br />
Trimmomatic See more https://github.com/usadellab/Trimmomatic.<br />
Tophat See more https://github.com/DaehwanKimLab/tophat.<br />

From the bam file:<br />

bam to Bigwig and create index:<br />
bamCoverage https://deeptools.readthedocs.io/en/develop/content/tools/bamCoverage.html<br />
Samtools http://www.htslib.org/doc/samtools-index.html<br />

Read_distrubition.py, input: bam file, gtf/gff/bed. See more http://rseqc.sourceforge.net/#genebody-coverage-py.

HTseq-count.py, input bam files, gtf/gff/bed. See more https://github.com/simon-anders/htseq.
Travel_Ratio.r visilzation R code for plotting the scatter plot using ggplot package. See more in https://ggplot2.tidyverse.org/.
The gene information from defined gene clusters can be found in the folder reference.

K-bining.py, input bam/bw file, gtf/gff/bed. See more http://rseqc.sourceforge.net/#genebody-coverage-py.
The gene information from defined gene clusters can be found in the folder reference.
