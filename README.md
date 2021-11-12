# GTDB2QIIME

Set of simple auxiliary python scripts to help create GTDB databases for annotation with QIIME

<br>
This collection of scripts is designed to facillitate QIIME annotations with GTDB reps ssu, or GTDB all ssu 
It consists of 2 separate small scripts, that can be run in Spyder, or reused for other purposes.
Since QIIME varies in dependancies and requirements on different operating systems, automated Qiime installation is not included,
and should be done following: https://docs.qiime2.org/2021.8/
<br><br>
Running a pipeline would consist of:<br>
-1. GTDB_ssu_download.py: to download recent GTDB ssu fasta files and taxonomy metadata<br>
-2. GTDB_protein_prep.py: to format GTDB ssu, with option to trim fragmented sequences below certain basepair length <br>



#### Licensing

The pipeline is licensed with standard MIT-license. <br>
If you would like to use this pipeline in your research, please cite the following papers: 
      
-Bolyen E, Rideout JR, Dillon MR, Bokulich NA, Abnet CC, Al-Ghalith GA, Alexander H, Alm EJ, Arumugam M, Asnicar F, Bai Y, Bisanz JE, Bittinger K, Brejnrod A, Brislawn CJ, Brown CT, Callahan BJ, Caraballo-Rodríguez AM, Chase J, Cope EK, Da Silva R, Diener C, Dorrestein PC, Douglas GM, Durall DM, Duvallet C, Edwardson CF, Ernst M, Estaki M, Fouquier J, Gauglitz JM, Gibbons SM, Gibson DL, Gonzalez A, Gorlick K, Guo J, Hillmann B, Holmes S, Holste H, Huttenhower C, Huttley GA, Janssen S, Jarmusch AK, Jiang L, Kaehler BD, Kang KB, Keefe CR, Keim P, Kelley ST, Knights D, Koester I, Kosciolek T, Kreps J, Langille MGI, Lee J, Ley R, Liu YX, Loftfield E, Lozupone C, Maher M, Marotz C, Martin BD, McDonald D, McIver LJ, Melnik AV, Metcalf JL, Morgan SC, Morton JT, Naimey AT, Navas-Molina JA, Nothias LF, Orchanian SB, Pearson T, Peoples SL, Petras D, Preuss ML, Pruesse E, Rasmussen LB, Rivers A, Robeson MS, Rosenthal P, Segata N, Shaffer M, Shiffer A, Sinha R, Song SJ, Spear JR, Swafford AD, Thompson LR, Torres PJ, Trinh P, Tripathi A, Turnbaugh PJ, Ul-Hasan S, van der Hooft JJJ, Vargas F, Vázquez-Baeza Y, Vogtmann E, von Hippel M, Walters W, Wan Y, Wang M, Warren J, Weber KC, Williamson CHD, Willis AD, Xu ZZ, Zaneveld JR, Zhang Y, Zhu Q, Knight R, and Caporaso JG. 2019. Reproducible, interactive, scalable and extensible microbiome data science using QIIME 2. Nature Biotechnology 37:852–857. https://doi.org/10.1038/s41587-019-0209-9
<br>
-Parks, D.H., et al. 2020. A complete domain-to-species taxonomy for Bacteria and Archaea. Nature Biotechnology, https://doi.org/10.1038/s41587-020-0501-8.


#### Contact:
-Hugo Kleimamp (Developer): H.B.C.Kleikamp@tudelft.nl<br> 
-Martin Pabst: M.Pabst@tudelft.nl<br>


#### Recommended links to other repositories:
https://github.com/qiime2/qiime2
