# Gene expression data for MRT paper
This folder contains filtered_gene_bc_matrices (cell line 60T) or filtered_feature_bc_matrix (cell lines 78T and 103T) folders and web_summary webpage from cellranger output.
Additionally, for multiplexed cell line 78T and 103T the result of demuxlet genotype assignment is located in demux_result folder.  
Correspondence between folder name and EGA accession numbers are listed below:

MRT_60T_CTRL	    = EGAN00002133134  
MRT_60T_SMB	      = EGAN00002133135  
MRT_78and103_CTRL	= EGAN00002580391, EGAN00002580392, EGAN00002580393, EGAN00002580394  
MRT_78and103_SMB	= EGAN00002580397, EGAN00002580398  

Metadata file metadata_filtered_single_cells.txt contains additional information about each cell, such as cell line, cell cycle score/phase, percentage of mitochondrial content and cluster number that was used in the manuscript.  
"cell_id" column contains the name of the barcode plus cell line / condition, i.e AAACCTGAGAAGGACA-1-CTRL60 or TTTGGAGTCTCTAAGG-1-SMB103.    
