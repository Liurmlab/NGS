# Sequence Processing Scripts

These scripts perform various sequence processing tasks including merging, quality control, trimming, and classification based on barcodes.

## Requirements

- Python 3.x
- VSEARCH
- FastQC
- Trimmomatic
- Biopython

## Installation

Ensure you have Python and the required tools installed on your system. You can install Biopython using the following command:

```sh
pip install biopython


Sequence Merging
1.Update the paths to your sequence files in the script:
input_forward = "/path/to/your/forward.fq"
input_reverse = "/path/to/your/reverse.fq"
output_merged = "/path/to/your/merged.fasta"
2.Run the script to merge the sequences using VSEARCH:
  python script.py

Quality Control and Trimming
1.Update the paths for FastQC and Trimmomatic processing:
input_fastq = "/path/to/your/merged.fasta"
output_dir = "/path/to/your/fastqc_output"
output_fastq = "/path/to/your/output_trimmed.fastq"
2.Run the script to perform quality control and trimming:
python script.py
