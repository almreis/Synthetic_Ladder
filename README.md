# Synthetic_Ladder
Demonstrating the use of Synthetic DNA ladders to measure variation and normalize samples

The simulated dataset (dataset.zip) contains the following columns:

The dataset contains the following columns:

1) Sequence: k-mer sequence 
2) S1: observed count for k-mer in sample 1  
3) S2: observed count for k-mer in sample 2  
4) Name: ID of synthetic ladder or bacterial genome from which the k-mer was originated   
5) S1.Expected_Abundance: expected abundance for k-mer in sample 1  
6) S1.Expected_Abundance: expected abundance for k-mer in sample 2  
7) Type: origin of the k-mer (synthetic ladder or bacterial) 

script.Rmd contains the R code to visualise the variation between samples 1 and 2 and also normalize them though using the Synthetic DNA Ladder.

script.html and script.pdf are the output of the R Markdown in HTML and PDF formats.
