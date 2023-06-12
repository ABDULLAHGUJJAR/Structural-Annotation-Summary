# Structural-Annotation-Summary
#To generate a summary using the AGAT (Annotation Gathering and Analysis Tool) for a Braker GTF file, you can follow these steps:

#Install AGAT: First, make sure you have AGAT installed on your system. You can find the installation instructions on the AGAT GitHub repository (https://github.com/NBISweden/AGAT).

conda install -c bioconda agat

#Prepare your Braker GTF file: Ensure that you have the Braker GTF file ready for analysis. You may need to run Braker, a gene annotation tool, to generate the GTF file from your genomic #data.

#Run the AGAT summary command: Open your terminal or command prompt and navigate to the directory where the Braker GTF file is located. Then, execute the following AGAT command:

agat_sp_statistics.pl --gff braker.gtf -o summary

#Replace "braker.gtf" with the actual filename of your Braker GTF file.

#Review the summary output: AGAT will generate a summary report based on the information extracted from the GTF file. The report will include statistics and information about gene #features, such as the number of genes, transcripts, exons, and various attributes.
#By following these steps, you should be able to use the AGAT tool to generate a summary for your Braker GTF file.
###############################################################################

conda install -c bioconda agat

agat_sp_statistics.pl --gff braker.gtf -o summary

##############################################################################
