# annoVIBRANT
Annotation-only wrapper for [VIBRANT](https://github.com/AnantharamanLab/VIBRANT)

Kristopher Kieft  
January 2022  

The purpose of this tool is to skip the virus prediction methods of VIBRANT and only annotate the input sequences with the exact same method used by VIBRANT. It is compatible with VIBRANT v1.2.1.  

### Setup
Run these two export commands or put them in your .bashrc/.bash_profile. Replace `full_path_here` with your actual path. Alternatively, you can skip this and specify these two folders with -d and -m, respectively.  

`export VIBRANTAUX='full_path_here/VIBRANT_v1.2.1/files/'`  

`export VIBRANTDB='full_path_here/VIBRANT_v1.2.1/databases/'`  

  
### Example Usage
annoVIBRANT.py -i example_seqs.fna -t 2 -o annoVIBRANT_output_folder  

_Note_: you can run proteins as well, input them with -i and specify -f prot. If you use proteins they just have to be in Prodigal format ("name_of_scaffold_#").  
