StrucGP
version:1.0.0
release date: 01/15/2020

Use of StucGP
1. To use StrucGP, double click main.exe, you can see the GUI interface along with a command console
2. Click 'step 1' tab, choose directories for MS files, protein database (fasta file) and glycan branch structure database 
3. Click 'step 2' tab, if you want to perform quantitative analysis, please select the corresponding label or click 'None' otherwise. Select fixed and variable modifications, if you need to add additional modifications, you can set modification name and monoisotopic mass by clicking 'Add to list' button.
4. Click 'step 3' tab, fill in the search settings, such as energy, oxonium ions and mass tolerance.
5. Click 'Run' button to start search. Once it successfully starts, a page with progress bar(s) should appear within a few minutes.

Please note:
1. MS file format must be .mzML so far. To avoid possible read errors in mzML file, Trans-Proteomic Pipeline is recommended for converting .raw to .mzML
2. Branch structure database was placed in the main folder named 'branch_structure.xlsx'. Up to now, there are a total of 20 branch structrues and we are devoted to achieve branch structure database independant searching for StrucGP currently
3. Quantification analysis of glycopeptide by StrucGP can use only TMT and iTRAQ, label free quantification will be supportd in later version.
4. Low energy and High energy spectra were used for glycan structure and peptide identification respectively, if you want to analysis MS file with single energy, set the high and low energy to the same.
5. Top_n: high energy spectra top peaks number selected for further identification 
    Oxo_top_n, Oxo_ess_n, Oxo_ess_mz: glycopeptide spectra filter parameters, top n peaks must contain Oxo_ess_n times Oxo_ess_mz
6. Result file will be generated in the same directory as the MS file after the searching finishes

If you have any questions or suggestions, please contact JiechenShenGlyco@163.com or post issues at Github(https://github.com/Sun-GlycoLab/StrucGP).