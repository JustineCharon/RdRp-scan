![RdRp-scan logo](https://user-images.githubusercontent.com/59948455/152477242-a6cec012-b8c1-42e9-969b-501bf6e14133.png)

# RdRp-Scan - Exploring the "dusk matter" of the RNA virosphere 

### RdRp sequence database
- ````RdRp-scan_0.90.info```` : List of accessions, taxonomy, viral species and putative host of RdRp-scan entries
- ````RdRp-scan_0.90.fasta```` : RdRp-scan RdRp core protein sequence database in fasta format
- ````RdRp-scan_0.90.dmnd```` : RdRp-scan RdRp core protein sequence database in diamond format (v.2.0.9)

### RdRp motif database (_Motif_db_)
- _{viral_order}_````.RdRp_motifs.fasta```` : RdRp motif sequences for each viral taxa

### RdRp phylogenies (_Phylogenies_)
- _{viral_phyla}_````.CLUSTALO_0.4.fasta```` : RdRp-alignments for each individual taxa _(Clustal-omega)_
- ````RdRp-scan.CLUSTALO_0.4.fasta```` : RdRp-alignment used to build the master RdRp tree _(Clustal-omega)_
- ````RdRp-scan.CLUSTALO_0.4.FAST_TREE```` : RdRp FastTREE file in Newick format

### HMM-RdRp database (_Profile_db_)
- ````RdRp_HMM_profile.db.h3?```` : RdRp HMM profile database _(Hmmer3-compatible ; v3.3)_
- _{viral-taxa}_````HMM_CLUSTALO.0.4.fasta```` : Clustal-omega alignments (40% identity cut-off) used to build HMM profiles.

````PDB_virRdRp_acc.txt```` : list of viral RdRp PDB accessions\
````RdRp_keyword.list```` : list of keyword used to retrieve RdRp-like accessions from NCBI Genbank \
````RdRp_InterPro_keyword.list```` : list of viral RdRp-like InterProScan entries
