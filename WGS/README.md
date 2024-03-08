# Parkinson's and whole genome sequencing project

This folder contains work I am doing for my whole genome sequencing project. I am using whole genome sequencing data I for chromosome 3 I obtained from Parkinson's Progressive Marker Initiative study.

What I am doing:
- pull out chromosome data for different subjects (create subset dataset)
- annotate subset dataset and use the annotated file to pull out different variants (functional, pathogenic, non-pathogenic)

Tools I am using (both are being run on command line on Unix system)
- VCFtools software
- Annovar annotation software
- Python

This folder contains files of two types:
- Jupyter notebook files: my Python work, if I need to check something in my subset files
- log files: These files are created by VCFtools and Annovar. They include command options (input, command directions, naming of the output file) that were used, any information the tool is outputing as it executes the command, writing of output file if successful (error or warning information if no output file created). My data files and subset files are all larger than GitHub size limit for each individual file of 100 MB, I am uploading log files.