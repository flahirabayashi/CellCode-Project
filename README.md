# CellCode-Project
Cell Code is a bioinformatics project that simulates cellular transcription and translation processes. It converts DNA sequences into RNA and then into aminoacids, providing a clear visualization of these biological processes.
## Features  
✔ DNA → RNA transcription  
✔ RNA → amino acid translation (3 reading frames)  
✔ Supports FASTA & FASTQ file formats  
✔ Three output modes:  
  - `complete` (DNA + RNA + amino acids)  
  - `dna` (DNA sequences only)  
  - `rna` (DNA & RNA sequences)  

## Usage  
1. Place your sequence file in the project directory  
2. Update the `file_path` in `cellcode.py`:  
   ```python
   file_path = 'your_sequence.fasta'  # or .fastq
   ```
3. Run the script\
   ```python cellcode.py```
   
## Technical Notes
✔ Implements codon translation table (64 codons)\
✔ Handles sequence offsets for reading frame analysis\
✔ Complexity: O(k×n) for k sequences of average length n
