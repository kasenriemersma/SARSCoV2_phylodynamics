# SARSCoV2_phylodynamics

The scripts in this repo are for downsampling a global SARS-CoV-2 and then further downsampling sequences exogenous to a region of interest in a time-stratified manner. Exogenous sequences are randomly downsampled and then exogenous sequences that are closest cophenetic neighbors to sequences from the region of interest are added back, if not already present.

The Exog_seq_selection bash script is a pipeline that will call the other scripts.

Full credit for filter_fasta_by_list_of_headers.py goes to StackExchange user 
[Kamil S Jaron](https://bioinformatics.stackexchange.com/users/57/kamil-s-jaron)
who provided the script in the StackExchange post found [here](https://bioinformatics.stackexchange.com/questions/3931/remove-delete-sequences-by-id-from-multifasta).
