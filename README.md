# DRAM-based_TRNG-PUF

sample-data:

<ul>

<li> 2 random page from each vendor is sampled.

<li> each sample file is a comma delimated csv file.

<li> contains total 5 columns

<li> column format- <i>b, w, p, b<sub>n</sub>, d</i>. Here, <i>d</i> is the 8 bit hex data (of <i>b<sub>n</sub></i>th bank) collected from <i>b</i>th bit of <i>w:w+7</i> word of <i>p</i>th page.
</ul>

file name format: page{<i>p</i>}\_bank{<i>b<sub>n</sub></i>}\_micron\_{<i>input\_pattern</i>}.csv
