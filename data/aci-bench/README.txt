ACI-Benchmark Data
---------------------

Train/validation/test data from the two challenges below, can be found in the challenge_data folder:
https://github.com/abachaa/MEDIQA-Chat-2023
https://www.imageclef.org/2023/medical/mediqa

Data for experimenting with ASR instead of human transcriptons or ASR-corrected data instead of ASR transcripts may be found in the src_experiment_data folder.

Each data split will have the src-target file (with an ID, dialogue, note column) denoted by a *.csv file, as well as a metadata file (with additional metadata such as patient name and chief complaints) denoted by a *_metadata.csv file.

To join dataframes, please use the id or encounter_id columns.