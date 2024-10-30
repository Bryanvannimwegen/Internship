This GitHub directory contains my main scripts used during my Internship project.

Files:
SRR_metadata_scrape: Scrapes all metadata based on an input query. Output can be used in "Auto_extract_Parallel_preprocessing_errorhandling".
Auto_extract_Parallel_preprocessing_errorhandling: Automatically preprocesses a set amount of samples extracted from the "SRR_metadata_scrape" file.
Picard_two_stream_overlapping_kmer_CNN: Main Two-stream CNN model that predicts readlength. Takes "Auto_extract_Parallel_preprocessing_errorhandling" output files as input.
