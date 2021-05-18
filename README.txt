Name:StrucGP
version:1.0.0
release date: 05/18/2021
developed by python3.9

System requirements
Operating system and software
Windows 10 or Windows 7 Service Pack 1 above, Windows Server 2012 or above.
Hardware
Intel or AMD x86-64 processor, 4.6 GHz processor with 16 GB RAM


Installation guide
StrucGP can be used without installation.


How to acquire StrucGP license to activate your StrucGP software:

1. You can input 'ipconfig/all' in your command prompt window(CMD) on Windows platform. Under "Ethernet adapter" you may find a string consisting of 12 hexadecimal digits after the "Physical Address", which is your device's media access control address(MAC Address). 

2. After getting your MAC address, you need to copy it next to "MAC" between the "####" chars.

3. Besides, in order to get closer contact with users. You need to fill all below items between the "####" chars. You can just send this README txt file to sun_glycolab@126.com after finish it and we will provide StrucGP license to you as soon as possible.

4.You will find a LIC file named StrucGP_license in our reply. Please put it in the same folder as the main.exe. The wrong path or license file may cause failure when you start program.

5. If there are any other errors when you activate or use StrucGP, Please contact with us via sun_glycolab@126.com/JiechenShenGlyco@163.com.
 

#####################################################################

MAC:

User Name:

Your e-mail address:

University or Organization name:

Country or Region:

Your Leader or Supervisor:

Your leader's e-mail: 

#####################################################################		



Instructions for use
1. Run main.exe file, you can see the GUI interface along with a command console.
2. Click 'step 1' tab, choose directories for MS files(mzML file), protein database (fasta file) and glycan branch structure database (branch_structure.xlsx).
3. Click 'step 2' tab, if you want to perform quantitative analysis, please select the corresponding label or click 'None' otherwise. Select fixed and variable modifications, if you need to add additional modifications, you can set modification name and monoisotopic mass by clicking 'Add to list' button.
4. Click 'step 3' tab, fill in the search settings, such as energy, oxonium ions and mass tolerance.
5. Click 'Run' button to start search. Once it successfully starts, a page with progress bar(s) should appear within a few minutes.
6. Result file will be generated in the same directory as the MS file after the searching finishes.


Demo
Instructions to run on data
1. Run main.exe file.
2. Click 'step 1' tab, choose directories for MS files(test.mzML), protein database (test.fasta) and glycan branch structure database (branch_structures.xlsx).
3. Click 'step 3' tab, click 'Run' button to start search.
Expected output
test.xlsx(result file), test.csv and test.log in the directory of test.mzML. 
Expected run time
about 30min


Noting
1. To avoid possible read errors in mzML file, Trans-Proteomic Pipeline is recommended for converting .raw to .mzML.
2. Up to now, there are a total of 17 branch structrues and we are devoted to achieve branch structure database independant searching for StrucGP currently.
3. Quantification analysis of glycopeptide by StrucGP can use only TMT and iTRAQ, label free quantification will be supportd in later version.
4. Low energy and High energy spectra were used for glycan structure and peptide identification respectively, if you want to analysis MS file with single energy, set the high and low energy to the same.
5. Top_n: high energy spectra top peaks number selected for further identification;
    Oxo_top_n, Oxo_ess_n, Oxo_ess_mz: glycopeptide spectra filter parameters, top n peaks must contain Oxo_ess_n times Oxo_ess_mz.

Contact
If you have any questions or suggestions, please contact sun_glycolab@126.com/JiechenShenGlyco@163.com or post issues at Github(https://github.com/Sun-GlycoLab/StrucGP).


