# myist_activity
Virtual design and specificity testing of RPL13A (Ribosomal protein L13a)

# Background
RPL13A (Ribosomal Protein L13a) is a structural component of the 60S ribosomal subunit and plays a crucial role in protein synthesis. Due to its stable expression across different tissues and experimental conditions, RPL13A is widely used as an internal control (housekeeping gene) in gene expression studies, including qPCR.

# Objectives
	1.	Retrieve the human RPL13A mRNA sequence from NCBI
	2.	Design specific PCR primers using Primer-BLAST
	3.	Evaluate primer quality (Tm, GC content, secondary structures)
	4.	Perform in-silico specificity analysis against the human genome

  # Methodology

Step 1: Sequence Retrieval
	•	Database: NCBI Gene
	•	Gene: RPL13A (Ribosomal Protein L13a)
	•	Organism: Homo sapiens
	•	Gene ID: 23521
	•	Reference mRNA: NM_012423.4
	•	The FASTA sequence of the transcript was used as the PCR template.

Step 2: Primer Design (Primer-BLAST)

Parameters used:
	•	PCR product size: 100–200 bp
	•	Melting temperature (Tm):
	•	Minimum: 57°C
	•	Optimum: 60°C
	•	Maximum: 63°C
	•	Primer location: Exon–exon junction (to avoid genomic DNA amplification)
	•	Specificity database: Human genome (Homo sapiens, taxid: 9606)

  # Results
.Designed Primer Sequences

Forward Primer (5′ → 3′)
code CCTGGAGGAGAAGAGGAAAGAGA

Reverse Primer (5′ → 3′)
code TTGAGGACCTCTGTGTATTTGTCAA

# Primer Characteristics

Parameter          Forward primer            Reverse primer
Length              23bp                       25bp
GC content          ~52%                       ~44%
Melting temp        ~60°C                      ~59°C


# PCR Product Information
	•	Expected amplicon size: ~150 bp
	•	Suitable for qPCR and gene expression analysis

# Specificity Analysis
	•	The primer pair shows 100% identity with the RPL13A gene
	•	No significant off-target binding detected in the human genome
	•	No pseudogene or unintended amplification within a 2 kb range
	•	Low self-complementarity → No primer-dimer formation

 # Final Specificity Statement

“The designed primer pair is highly specific to the human RPL13A gene and does not show significant off-target amplification in the Homo sapiens genome, making it suitable for reliable gene expression analysis.”

# Conclusion

This in-silico analysis successfully designed and validated a specific and efficient primer pair for RPL13A, a ribosomal protein essential for protein synthesis. The primers meet all standard qPCR requirements and can be reliably used as a housekeeping gene control in expression studies.






  
  
