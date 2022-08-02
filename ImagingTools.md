# Ontario Brain Institute Imaging Tools

Please select the imaging tool you'd like to look at:

    
    
<details>
<summary>MRI</summary> 
    &nbsp  
    <blockquote><details><summary> Data Collection Pipelines</summary>
MRI data is collected and processed in the MRI scanner before undergoing data curation.
</details></blockquote>

<blockquote><details><summary> Data Curation and Processing Pipelines</summary>
&nbsp 
    
| Tool/Pipeline | Description | Requirements | Compute Location | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| Naming convention pipeline | Pipeline that re-names data to be more easily processed on SPReD.<details><summary>License</summary>Creative Commons Attribution 3.0</details> | N/A | [Brain-CODE](https://www.braincode.ca/) | All |
| Scan Aquisition Pipeline | Pipeline that checks to see if there's a scan acquisition protocol which outlines specific criteria for scans.<details><summary>License</summary>Creative Commons Attribution 3.0</details> | N/A |[Brain-CODE](https://www.braincode.ca/) | All |
| [fBIRN](https://www.nitrc.org/projects/fbirn/) | Quality control for any changes in function in fMRI. Stores data in HTML file. Used for non-human/phantom data. <details><summary>License</summary>BSD and BIRN</details> | N/A | At the lab | All |
| [MRIQC](https://github.com/nipreps/mriqc/tree/c57059ee82c2bf07d188dbb588407a41116a1a61) | Program run on human brain scans and structural scans to provide summary variables. Is used to track outliers and indicate any potential problems in MRI function. Stores data in sessions on SPReD. Designed originally to handle large datasets.<details><summary>License</summary>3-clause BSD</details> <details><summary>Tool Citation(s) </summary>    Esteban O, Birman D, Schaer M, Koyejo OO, Poldrack RA, Gorgolewski KJ; MRIQC: Advancing the Automatic Prediction of Image Quality in MRI from Unseen Sites; PLOS ONE 12(9):e0184661; doi:[10.1371/journal.pone.0184661](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0184661).</details> <details><summary>Relevant Publications</summary>[Esteban et al., 2017](https://doi.org/10.1101/216671), [Esteban et al.,2018](https://doi.org/10.1007/978-3-030-01364-6_21), [Sánchez et al., 2021]( https://doi.org/10.1101/2021.02.01.428681), [Provins et al., 2022](https://doi.org/10.31219/osf.io/8mcyz), [Reguig et al., 2022](https://doi.org/10.48550/arXiv.2205.15898)</details> | Large size CPU |  &emsp;&emsp;&emsp;&emsp; [Brain-CODE](https://www.braincode.ca/) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | CAN-BIND, ONDRI |
| [ANT](http://stnava.github.io/ANTs/) | Pipeline for registration to a template image (normalization). <details><summary>License</summary>Apache Version 2.0 </details> <details><summary>Tool Citation(s) </summary>Tustison, N. J., Cook, P. A., Klein, A., Song, G., Das, S. R., Duda, J. T., Kandel, B. M., van Strien, N., Stone, J. R., Gee, J. C., &amp; Avants, B. B. (2014). Large-scale evaluation of ants and freesurfer cortical thickness measurements. NeuroImage, 99, 166–179. [https://doi.org/10.1016/j.neuroimage.2014.05.044](https://www.sciencedirect.com/science/article/pii/S1053811914004091?via%3Dihub) </details> <details><summary>Relevant Publications</summary>[Walimuni et al., 2011](https://doi.org/10.1016/j.compbiomed.2010.10.009), [Sanchez et al., 2012]( https://doi.org/10.1080/87565641.2012.688900), [Hart et al., 2017](https://doi.org/10.1016/j.nicl.2017.04.026), [Wang et al., 2017]( https://www.frontiersin.org/articles/10.3389/fninf.2017.00017), [Birchfield et al., 2022](https://doi.org/10.48550/arXiv.2204.03576) </details> | N/A | [Brain-CODE](https://www.braincode.ca/) | CAN-BIND, ONDRI|
| [Free Surfer - recon-all function](https://surfer.nmr.mgh.harvard.edu/fswiki/recon-all) | Function that conduct measurements of volumetric/thickness in all brain regions and looks at volume of grey matter, white matter, CSF in the brain. Takes 20 minutes per session. All results stored in session. <details><summary>License</summary>GNU General Public License Version 2.0 </details> <details><summary>Tool Citation(s) </summary> Citation will depend on what the recon-all function was used for. Citation information can be found [here](https://surfer.nmr.mgh.harvard.edu/fswiki/FreeSurferMethodsCitation).</details> <details><summary>Relevant Publications</summary> [Keller et al., 2012](https://doi.org/10.1007/s12021-012-9147-0), [Ellis et al., 2016](https://doi.org/10.1186/s13742-016-0147-0-o), [Muschelli et al., 2018](https://doi.org/10.12688/f1000research.14361.1), [Wu et al., 2018](https://doi.org/10.1002/hbm.24213), [Hou et al., 2020](https://doi.org/10.1371/journal.pone.0230754) </details>| Large size CPU | Frontenac | CAN-BIND, ONDRI|
| Scan Rating Service with notification | Service which notifies researcher to rate the scan. Once done for each scan, a report is generated with the ratings of all scans. All metadata is compared against a set of known parameters and deviations are flagged. <details><summary>License</summary>Creative Commons Attribution 3.0</details> | N/A | [Brain-CODE](https://www.braincode.ca/) | CAN-BIND, ONDRI |
| [ICN](https://www.nitrc.org/projects/icn_atlas/) | Software that uses fMRI data to create a functional network. Was used by CAN-BIND researchers to isolates 10 different networks. <details><summary>License</summary>Creative Commons Attribution 4.0</details> <details><summary>Tool Citation(s) </summary> Kozák, L. R., van Graan, L. A., Chaudhary, U. J., Szabó, Á. G., &amp; Lemieux, L. (2017). ICN_Atlas: Automated description and quantification of functional MRI activation patterns in the framework of Intrinsic Connectivity Networks. NeuroImage, 163, 319–341. [https://doi.org/10.1016/j.neuroimage.2017.09.014](https://doi.org/10.1016/j.neuroimage.2017.09.014) </details> <details><summary>Relevant Publications</summary> [Bushov et al., 2020](https://doi.org/10.1016/j.procs.2020.02.121), [Bukhari-Parlakturk et al., 2021](https://doi.org/10.1101/2021.05.14.21257239), [Marstaller et al., 2021](https://doi.org/10.1002/hbm.25199), [Vaudano et al., 2021](https://doi.org/10.1007/s10548-021-00857-x), [Elin et al., 2022](https://doi.org/10.3389/fnhum.2022.791577) </details> | N/A | At the lab | CAN-BIND |
| [OPPNI Pipeline](https://github.com/strotherlab/oppni) | Pipeline used for fMRI pre-processing. <details><summary>License</summary>GNU General Public License Version 3.0</details> <details><summary>Tool Citation(s) </summary> Strother SC, Anderson J, Hansen LK, Kjems U, Kustra R et al. (2002): The Quantitative Evaluation of Functional Neuroimaging Experiments: The NPAIRS Data Analysis Framework. NeuroImage 15:747–771 </details> <details><summary>Relevant Publications</summary> #To be filled </details> | Large size CPU | Frontenac | ONDRI |
| [SABRE](https://sabre.brainlab.ca/docs/index.html#) | Pipeline used for the identification of volumetrics in lesion data for structural MRI images. <details><summary>License</summary>GNU General Public License Version 3.0</details> <details><summary>Tool Citation(s) </summary> Dade L.A., Gao F.Q., Kovacevic N., Roy P., Rockel C., O'Toole C.M., Lobaugh N.J., Feinstein A., Levine B., Black S.E.  (2004).  Semiautomatic brain region extraction: a method of parcellating brain regions from structural magnetic resonance images. Neuroimage, 22, 1492-502. </details> <details><summary>Relevant Publications</summary> [Dade et.al., 2004](https://doi.org/10.1016/j.neuroimage.2004.03.023), [Ramirez et.al., 2011](https://doi.org/10.1016/j.neuroimage.2010.09.013), [Ramirez et.al., 2013](https://doi.org/10.1007/s10548-012-0228-z), [Ramirez et.al., 2020](https://www.frontiersin.org/articles/10.3389/fneur.2020.00847) </details> | N/A | At the lab | ONDRI |
| [Lesion Explorer](https://sabre.brainlab.ca/docs/processing/stage7.html#lesion-explorer-le) | Tool used for semi-automatic lesion segmentation. <details><summary>License</summary>GNU General Public License Version 3.0</details> <details><summary>Tool Citation(s) </summary> </details> <details><summary>Relevant Publications</summary>  </details> | N/A | At the lab | ONDRI |
| [FLEX](https://sabre.brainlab.ca/docs/processing/stage7.html#fuzzy-lesion-extractor-flex-coming-soon) (Coming soon!) | Tool used for fuzzy lesion extraction for FLAIR images. <details><summary>License</summary>GNU General Public License Version 3.0</details> <details><summary>Tool Citation(s)</summary>Gibson E., Gao F., Black S.E., Lobaugh N.J.  (2010).  Automatic segmentation of white matter hyperintensities in the elderly using FLAIR images at 3T. Journal of Magnetic Resonance Imaging, 31, 1311-22.</details> <details><summary>Relevant Publications</summary> </details> | N/A | At the lab | ONDRI |
| [Sunnybrook ITK-SNAP Extension](https://github.com/sbips/itksnapsb) | Software that allows for editing and viewing of structural MRI data. <details><summary>License</summary>GNU General Public License Version 3.0</details> <details><summary>Tool Citation(s) </summary> Ask Chris Scott </details> <details><summary>Relevant Publications</summary> To be filled </details> | N/A | At the lab | ONDRI |
| [ANALYZE Software](https://analyzedirect.com) | Software used for manual editing and checking procedures of structural MRI data. <details><summary>License</summary>Not sure...</details> <details><summary>Tool Citation(s) </summary> To be filled </details> <details><summary>Relevant Publications</summary>To be filled </details> | N/A | At the lab | ONDRI |
| [FSL - FLIRT](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FLIRT) | Tool that is used for intra and inter modal brain image registration. <details><summary>License</summary> Oxford </details> <details><summary>Tool Citation(s) </summary> M. Jenkinson and S.M. Smith. A global optimisation method for robust affine registration of brain images. Medical Image Analysis, 5(2):143-156, 2001.</br> <br>M. Jenkinson, P.R. Bannister, J.M. Brady, and S.M. Smith. Improved optimisation for the robust and accurate linear registration and motion correction of brain images. NeuroImage, 17(2):825-841, 2002.</br> <br>Greve, D.N. and Fischl, B. Accurate and robust brain image alignment using boundary-based registration. NeuroImage, 48(1):63-72, 2009. </br> </details> <details><summary>Relevant Publications</summary>[Jenkinson & Smith, 2001](https://doi.org/10.1016/s1361-8415(01)00036-6), [Smith et al., 2004](https://doi.org/10.1016/j.neuroimage.2004.07.051), [Lancaster et al., 2007](https://doi.org/10.1002/hbm.20345), [Ramirez et al., 2011](https://doi.org/10.1016/j.neuroimage.2010.09.013), [Jenkinson et al., 2012](https://doi.org/10.1016/j.neuroimage.2011.09.015), [Muschelli et al., 2015](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4911193/) </details> | >16 GB RAM, Swap space at least equal to GB of RAM, Disk space at least 10 times the size of data sets | At the lab | ONDRI |
| [FSL - BET](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/BET) | Tool that is used to extract the intra-cranial volume for each subject by removal of the skull and infratentorial structures. <details><summary>License</summary> Oxford </details> <details><summary>Tool Citation(s) </summary> S.M. Smith. Fast robust automated brain extraction. Human Brain Mapping, 17(3):143-155, November 2002. </br> <br>If skull and scalp surface extraction functions are also used, please also reference the following:</br> <br> M. Jenkinson, M. Pechaud, and S. Smith. BET2: MR-based estimation of brain, skull and scalp surfaces. In Eleventh Annual Meeting of the Organization for Human Brain Mapping, 2005. </details> <details><summary>Relevant Publications</summary> [Smith et al., 2004](https://doi.org/10.1016/j.neuroimage.2004.07.051), [Smith et al., 2006](https://doi.org/10.1016/j.neuroimage.2006.02.024), [Nestor et al., 2013](https://doi.org/10.1016/j.neuroimage.2012.10.081), [Cengiz et al., 2022](https://doi.org/10.1007/s10334-022-01030-6), [Diaz-Hurtado et al., 2022](https://doi.org/10.1007/s00234-022-03019-3) </details> | >16 GB RAM, Swap space at least equal to GB of RAM, Disk space at least 10 times the size of data sets | At the lab | ONDRI |
| [N3 Software](https://github.com/BIC-MNI/N3) | Software that corrects for intensity nonuniformity in MRI data by using nonparametric nonuniform intensity normalization. <details><summary>License</summary> https://github.com/BIC-MNI/N3/blob/master/COPYING </details> <details><summary>Tool Citation(s) </summary> Sled JG, Zijdenbos AP, Evans AC. A nonparametric method for automatic correction of intensity nonuniformity in MRI data. IEEE Trans Med Imaging 1998;17:87–97. </details> <details><summary>Relevant Publications</summary> [Jones & Wong, 2002](https://doi.org/10.1117/12.467069), [Zhuge et al., 2009](https://doi.org/10.1016/j.compmedimag.2008.09.004), [Gibson et al., 2010](https://doi.org/10.1002/jmri.22004), [Tustison et al., 2010](https://doi.org/10.1109/TMI.2010.2046908), [Lin et al., 2011](https://doi.org/10.1118/1.3519869), [Larsen et al., 2014](https://doi.org/10.1007/978-3-319-12289-2_1) </details> | Edit Later... | At the lab | ONDRI |
| [FSL - FAST](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FAST?highlight=%28mfast%29) (Previously mfast) | Software used for bias correction and to correct intensity inhomogeneities present in MRI data. <details><summary>License</summary> Oxford </details> <details><summary>Tool Citation(s) </summary> Zhang, Y. and Brady, M. and Smith, S. Segmentation of brain MR images through a hidden Markov random field model and the expectation-maximization algorithm. IEEE Trans Med Imag, 20(1):45-57, 2001. </details> <details><summary>Relevant Publications</summary> [Smith et al., 2004]( https://doi.org/10.1016/j.neuroimage.2004.07.051), [Gibson et al., 2010](https://doi.org/10.1002/jmri.22004), [Glasser et al., 2013](https://doi.org/10.1016/j.neuroimage.2013.04.127), [Droby et al., 2021](https://doi.org/10.1371/journal.pone.0254597) </details> | >16 GB RAM, Swap space at least equal to GB of RAM, Disk space at least 10 times the size of data sets | At the lab | ONDRI |
| [SPM Software](https://www.fil.ion.ucl.ac.uk/spm/) | Collection of MATLAB functions and subroutines that uses a thresholded probabilistic white matter template to create a white matter mask. <details><summary>License</summary>GNU General Public License Version 2.0</details> <details><summary>Tool Citation(s) </summary>Litvak, V., Mattout, J., Kiebel, S., Phillips, C., Henson, R., Kilner, J., Barnes, G., Oostenveld, R., Daunizeau, J., Flandin, G., Penny, W., & Friston, K. (2011). EEG and MEG Data Analysis in SPM8. Computational Intelligence and Neuroscience, 2011, e852961. https://doi.org/10.1155/2011/852961</details> <details><summary>Relevant Publications</summary> [Tzourio-Mazoyer et al., 2002](https://doi.org/10.1006/nimg.2001.0978), [Ashburner, 2009](https://doi.org/10.1016/j.mri.2009.01.006), [Gibson et al., 2010](https://doi.org/10.1002/jmri.22004), [Kazemi & Noorizadeh, 2014](https://pubmed.ncbi.nlm.nih.gov/25505764/) </details> | MATLAB | At the lab | ONDRI |
| [Standards (Shiny) App](https://github.com/ondri-nibs/standards_app) | Performs standard checks on ONDRI data <details><summary>License</summary>GNU General Public License Version 3.1</details> | R, Rstudio | At the lab | ONDRI| 
| [Data Preparation (Shiny) App](https://github.com/ondri-nibs/dataprep_app) | Prepares ONDRI data for outlier analysis. <details><summary>License</summary>GNU General Public License Version 3.0</details> | R, RStudio, [GSVD](https://github.com/derekbeaton/GSVD) and [ours](https://github.com/derekbeaton/OuRS) R Packages | At the lab | ONDRI| 
| [Outliers (Shiny) App](https://github.com/ondri-nibs/outliers_app) | Performs outlier analyses on ONDRI data <details><summary>License</summary>GNU General Public License Version 3.2</details> | R, Rstudio | At the lab | ONDRI| 
| [OSIRIX](https://www.osirix-viewer.com/) | Software used for confirmation of de-identification of MRI data by EpLink researchers. <details><summary>License</summary>Perpetual License </details> <details><summary>Tool Citation(s) </summary> Rosset, A., Spadola, L., & Ratib, O. (2004). OsiriX: An Open-Source Software for Navigating in Multidimensional DICOM Images. Journal of Digital Imaging, 17(3), 205–216. https://doi.org/10.1007/s10278-004-1014-6 </details><details><summary>Relevant Publications</summary> [Ratib & Rosset, 2006](https://doi.org/10.1007/s11548-006-0056-2), [Vides Canas et al., 2007](https://doi.org/10.1109/IEMBS.2007.4352974), [Fortin & Battié, 2012](https://doi.org/10.2522/ptj.20110380), [Deora et al., 2020](https://doi.org/10.1016/j.wneu.2020.05.146) </details>| Only compatible on Mac Computers, >6 GB RAM | At the lab | EpLink |
| [MANGO](https://ric.uthscsa.edu/mango/mango.html) | Software used for confirmation of de-identification of MRI data by EpLink researchers. <details><summary>License</summary> Freeware License </details> <details><summary>Tool Citation(s) </summary> In-text citation:<br> Lancaster, Martinez; www.ric.uthscsa.edu/mango</details> <details><summary>Relevant Publications</summary> To be filled </details> | N/A | At the lab | EpLink |
| [fMRIPrep](https://fmriprep.org/en/stable/) | Preprocessing pipeline for task-based and resting-state functional MRI | N/A | At the lab | POND |
| [Bpipe](https://github.com/ssadedin/bpipe/) | Preprocessing pipeline (masking, image registration, etc). Needed for CIVET/MAGeT/Freesurfer. <details><summary>Tool Citation(s)</summary>Sadedin S, Pope B & Oshlack A, Bpipe: A Tool for Running and Managing Bioinformatics Pipelines, Bioinformatics</details> | N/A | At the lab | POND |
| [CIVET](http://www.bic.mni.mcgill.ca/ServicesSoftware/CIVET-2-1-0-Table-of-Contents) | Cortical morphometry pipeline that uses deformable models to fit and measure the human cortex. Similar function to Freesurfer. | N/A | At the lab | POND |
| [MAGeT](https://github.com/CobraLab/MAGeTbrain) | General purpose segmentation pipeline that does automatic template generation for multi-atlas segmentation. <details><summary>Tool Citation(s)</summary>Pipitone J, Park MT, Winterburn J, et al. Multi-atlas segmentation of the whole hippocampus and subfields using multiple automatically generated templates. Neuroimage. 2014<br></br> M Mallar Chakravarty, Patrick Steadman, Matthijs C van Eede, Rebecca D Calcott, Victoria Gu, Philip Shaw, Armin Raznahan, D Louis Collins, and Jason P Lerch. Performing label-fusion-based segmentation using multiple automatically generated templates. Hum Brain Mapp, 34(10):2635–54, October 2013. (doi:10.1002/hbm.22092)</details> | Python 3, [ANTs](http://stnava.github.io/ANTs/) (with MINC enabled), [minc-toolkit-v2](https://en.wikibooks.org/wiki/MINC/Introduction), [pyminc](https://github.com/Mouse-Imaging-Centre/pyminc), [minc-stuffs](https://github.com/Mouse-Imaging-Centre/minc-stuffs), [qbatch](https://github.com/pipitone/qbatch) (for cluster integration), [gnu-parallel](https://www.gnu.org/software/parallel/) | At the lab | POND |
| [Freesurfer](https://surfer.nmr.mgh.harvard.edu/fswiki/FreeSurferBeginnersGuide) | Set of software tools for study of cortical and subcortical anatomy. Similar function to CIVET. | Linux/OSX Operating Systems| At the lab | POND |
| [Pydpiper](https://github.com/Mouse-Imaging-Centre/pydpiper) | Neuroimaging registration toolkit written in Python. | N/A | At the lab | POND |
| [Minc-toolkit2](https://en.wikibooks.org/wiki/MINC/Introduction) | Set of software tools for advanced image processing, pipelining, statistical analysis, and visualization. | N/A | At the lab | POND |
</details></blockquote>

<blockquote><details><summary>Data Analysis Pipeline</summary>
&nbsp

| Tool/Pipeline | Description | Requirements | Compute Location | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| RStudio | Used for data visualization for structural MRI data | N/A | At the lab | ONDRI |
| MATLAB | Used for data visualization for structural MRI data | N/A | At the lab | ONDRI |
| SPSS | Used for testing of hypotheses by ONDRI resarchers | N/A | At the lab | ONDRI |
| [Minc-toolkit2](https://en.wikibooks.org/wiki/MINC/Introduction) | Set of software tools for advanced image processing, pipelining, statistical analysis, and visualization. | N/A | At the lab | POND |
| [FSL](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSL) | Library of analysis tools for fMRI, MRI, and DTI brain imaging data. | N/A | At the lab | POND |
    
</blockquote></details>
</details>

<details>
<summary>EEG</summary>
&nbsp 
<blockquote><details><summary> Data Collection Pipelines</summary>
&nbsp 
    
| Tool/Pipeline | Description | Requirements | Compute Location | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| [Natus NeuroWorks EEG](https://neuro.natus.com/products-services/natus-neuroworks-eeg-software) | Data collection platform for EEG in the lab <details><summary>License</summary> Proprietary </details> <details><summary>Tool Citation(s) </summary> To be filled </details> <details><summary>Relevant Publications</summary>To be filled </details>| Mid-size CPU | At the lab | EpLink|
</details></blockquote>

<blockquote><details><summary> Data Curation and Processing Pipelines</summary>
&nbsp 
    
| Tool/Pipeline | Description | Requirements | Compute Location | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| Naming convention pipeline | Pipeline that re-names data to be more easily processed on SPReD.<details><summary>License</summary>Creative Commons Attribution 3.0</details> | N/A | [Brain-CODE](https://www.braincode.ca/) | All |
| [EEGLAB](https://sccn.ucsd.edu/eeglab/index.php) | Software that is used for the conversion of EEG data into EDF format and the normalization and standardization of EEG data. <details><summary>License</summary>MIT License </details> <details><summary>Tool Citation(s) </summary> Delorme, A., & Makeig, S. (2004). EEGLAB: An open source toolbox for analysis of single-trial EEG dynamics including independent component analysis. Journal of Neuroscience Methods, 134(1), 9–21. https://doi.org/10.1016/j.jneumeth.2003.10.009 </details> <details><summary>Relevant Publications</summary> [Delorme & Makeig, 2004](https://doi.org/10.1016/j.jneumeth.2003.10.009), [Makeig et al., 2004](https://doi.org/10.1016/j.tics.2004.03.008), [Delorme et al., 2007](https://doi.org/10.1016/j.neuroimage.2006.11.004), [Delorme et al., 2011](https://doi.org/10.1155/2011/130714), [Martínez-Cancino et al., 2021](https://doi.org/10.1016/j.neuroimage.2020.116778) </details>| MATLAB, > 8 GB and multi-core 64-bit processors recommended for large datasets | At the lab | CAN-BIND|
| [ERPEEG](https://github.com/EEGSignalProcessing/ERPEEG) | MATLAB app that is used for streamlined processing of ERP data <details><summary>License</summary> GNU General Public License Version 3.0 </details> <details><summary>Tool Citation(s) </summary> To be filled </details> <details><summary>Relevant Publications</summary>To be filled </details>| MATLAB, EEGLAB, FASTICA, tight_subplot.m | At the lab | CAN-BIND |
| [TMSEEG](http://www.tmseeg.com/) | Streamlined app that allows for EEG data collection during TMS application <details><summary>License</summary> GNU General Public License Version 3.0 </details> <details><summary>Tool Citation(s) </summary> Atluri, S., Frehlich, M., Mei, Y., Garcia Dominguez, L., Rogasch, N. C., Wong, W., Daskalakis, Z. J., & Farzan, F. (2016). TMSEEG: A MATLAB-Based Graphical User Interface for Processing Electrophysiological Signals during Transcranial Magnetic Stimulation. Frontiers in Neural Circuits, 10. https://www.frontiersin.org/articles/10.3389/fncir.2016.00078 </details> <details><summary>Relevant Publications</summary> [Atluri et al., 2016](https://www.frontiersin.org/articles/10.3389/fncir.2016.00078), [Farzan et al., 2017](https://doi.org/10.1038/s41598-017-07613-x), [Tremblay et al., 2019](https://doi.org/10.1016/j.clinph.2019.01.001), [Dhami et al., 2020](https://doi.org/10.1093/cercor/bhaa004), [Bertazzoli et al., 2021](https://doi.org/10.1016/j.neuroimage.2021.118272) </details> | MATLAB, EEGLAB, FASTICA, tight_subplot.m | At the lab | CAN-BIND |
| [DATA2BIDS](https://github.com/SIMEXP/Data2Bids) | Software that assists in the acquisition of EEG data and the conversion of EEG data to EDF format and packaging to BIDS format. <details><summary>License</summary> MIT License </details> <details><summary>Tool Citation(s) </summary> Oostenveld, R., Fries, P., Maris, E., & Schoffelen, J.-M. (2010). FieldTrip: Open Source Software for Advanced Analysis of MEG, EEG, and Invasive Electrophysiological Data. Computational Intelligence and Neuroscience, 2011, e156869. https://doi.org/10.1155/2011/156869 </details> <details><summary>Relevant Publications</summary>[Oostenveld et al., 2010](https://doi.org/10.1155/2011/156869), [Holdgraf et al., 2019](https://doi.org/10.1038/s41597-019-0105-7), [Pernet et al., 2019](https://doi.org/10.1038/s41597-019-0104-8), [Schoffelen et al., 2019](https://doi.org/10.1038/s41597-019-0020-y), [Vaghari et al., 2022](https://doi.org/10.1016/j.neuroimage.2022.119344) </details> | [BIDS Validator](https://github.com/bids-standard/bids-validator), nibabel, numpy | [Brain-CODE](https://www.braincode.ca/) | EpLink |

</details></blockquote>

<blockquote><details><summary> Data Analysis Pipelines</summary></details></blockquote>
    
</details>

<details>
<summary>DTI</summary>
&nbsp 
<blockquote><details><summary> Data Collection Pipelines</summary></details></blockquote>
  
<blockquote><details><summary> Data Curation and Processing Pipelines</summary>
&nbsp
    
| Tool/Pipeline | Description | Requirements | Compute Location | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| [SABRE](https://sabre.brainlab.ca/docs/index.html#) | Pipeline used for the identification of volumetrics in lesion data for structural MRI images. <details><summary>License</summary>GNU General Public License Version 3.0</details> <details><summary>Tool Citation(s) </summary> Dade L.A., Gao F.Q., Kovacevic N., Roy P., Rockel C., O'Toole C.M., Lobaugh N.J., Feinstein A., Levine B., Black S.E.  (2004).  Semiautomatic brain region extraction: a method of parcellating brain regions from structural magnetic resonance images. Neuroimage, 22, 1492-502. </details> <details><summary>Relevant Publications</summary> [Dade et.al., 2004](https://doi.org/10.1016/j.neuroimage.2004.03.023), [Ramirez et.al., 2011](https://doi.org/10.1016/j.neuroimage.2010.09.013), [Ramirez et.al., 2013](https://doi.org/10.1007/s10548-012-0228-z), [Ramirez et.al., 2020](https://www.frontiersin.org/articles/10.3389/fneur.2020.00847) </details> | N/A | At the lab | ONDRI |
| [Lesion Explorer](https://sabre.brainlab.ca/docs/processing/stage7.html#lesion-explorer-le) | Tool used for semi-automatic lesion segmentation. <details><summary>License</summary>GNU General Public License Version 3.0</details> <details><summary>Tool Citation(s) </summary> </details> <details><summary>Relevant Publications</summary>  </details> | N/A | At the lab | ONDRI |
| [FLEX](https://sabre.brainlab.ca/docs/processing/stage7.html#fuzzy-lesion-extractor-flex-coming-soon) (Coming soon!) | Tool used for fuzzy lesion extraction for FLAIR images. <details><summary>License</summary>GNU General Public License Version 3.0</details> <details><summary>Tool Citation(s)</summary>Gibson E., Gao F., Black S.E., Lobaugh N.J.  (2010).  Automatic segmentation of white matter hyperintensities in the elderly using FLAIR images at 3T. Journal of Magnetic Resonance Imaging, 31, 1311-22.</details> <details><summary>Relevant Publications</summary> </details> | N/A | At the lab | ONDRI |
| [FSL - FAST](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FAST?highlight=%28mfast%29) (Previously mfast) | Software used for bias correction and to correct intensity inhomogeneities present in MRI data. <details><summary>License</summary> Oxford </details> <details><summary>Tool Citation(s) </summary> Zhang, Y. and Brady, M. and Smith, S. Segmentation of brain MR images through a hidden Markov random field model and the expectation-maximization algorithm. IEEE Trans Med Imag, 20(1):45-57, 2001. </details> <details><summary>Relevant Publications</summary> [Smith et al., 2004]( https://doi.org/10.1016/j.neuroimage.2004.07.051), [Gibson et al., 2010](https://doi.org/10.1002/jmri.22004), [Glasser et al., 2013](https://doi.org/10.1016/j.neuroimage.2013.04.127), [Droby et al., 2021](https://doi.org/10.1371/journal.pone.0254597) </details> | >16 GB RAM, Swap space at least equal to GB of RAM, Disk space at least 10 times the size of data sets | At the lab | ONDRI |
| 3D Slicer - Rician LMMSE Image Filter Module | DTI data is moderately filtered to alleviate the effect of the Rician noise. Accepts NRRD format. | N/A | At the lab | ONDRI |
| DTIPrep | Takes output of Filter. Applied to DTI data to reject the diffusion volumes affected by various DWI artifacts and corrects the DTI data for eddy current and motion artifacts. | N/A | At the lab | ONDRI |
| Camino - RESTORE algorithm | Conducts robust tensorfitting to estimate voxelwise diffusion tensors from the DTI data using an iteratively reweighted least-square regression algorithm. Used to capture and remove outlier voxels from the tensor fitting. | N/A | At the lab | ONDRI |
| MATLAB code | Voxel wise DTI metric check up, removing voxels with negative eigenvalues or with MD, AD, AND RD higher than 5.5 mm2/sec. | N/A | At the lab | ONDRI |    
    
</details></blockquote>

<blockquote><details><summary> Data Analysis Pipelines</summary>
&nbsp
    
| Tool/Pipeline | Description | Requirements | Compute Location | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| 3D Slicer - DWIConverter Module | Converts data to NIFTI format and converts data to NIFTI format | N/A | At the lab | ONDRI | 
| 3D Slicer - Robust Brain Extraction (ROBEX) Module | Performs skull stripping | N/A | At the lab | ONDRI | 
| FSL - FLIRT | Used for linear registration to T1 | N/A | At the lab | ONDRI | 
| FSL - BBR  | Used for further adjustments for linear registration to T1 mas | N/A | At the lab | ONDRI | 
| FSL - BET2 | Performs skull stripping | N/A | At the lab | ONDRI | 
| 3D Slicer - DWIConverter Module | Converts the raw DTI data to NRRD format.  | N/A | At the lab | ONDRI | 
| 3D Slicer - DWIConverter Module | Converts the quality controlled DTI data obtanined from DTIPrep in NRRD format to NIFTI format.  | N/A | At the lab | ONDRI | 
| FSL - BBR Tool | Used for linear registration of the b0 volume in the DTI data to the corresponding T1-weighted image. | N/A | At the lab | ONDRI | 
| FSL - FLIRT - applyxfm4D | Applies the transformation obtained from the previous step (BBR) to all the gradient volumes in DTI data to transfer the DTI data to the native T1-weighted space.  | N/A | At the lab | ONDRI | 
| FSL - BET2 | Used for skull stripping of DTI data | N/A | At the lab | ONDRI | 
| ANTs - SyN Registration Algorithm | Used for non-linear registration of the b=0 image in the DTI data to the T2-weighted image. Used to remove EPI artifacts.  | N/A | At the lab | ONDRI | 
| ANTs - antsApplyTransforms | Used for multiresolution nonlinear registration of DTI data to registered T2 images.  | N/A | At the lab | ONDRI | 
| Camino - RESTORE algorithm | Conducts robust tensorfitting to estimate voxelwise diffusion tensors from the DTI data using an iteratively reweighted least-square regression algorithm. Used to capture and remove outlier voxels from the tensor fitting. | N/A | At the lab | ONDRI | 
| FSL - dtifit | DTI scalar metrics calculation | N/A | At the lab | ONDRI | 
| MATLAB | Conducts region of interest (ROI) analysis based on the regions provided by ONDRI SABRE lesion masks. | N/A | At the lab | ONDRI | 

</details></blockquote>
</details>

<details>
<summary>TMS</summary>
&nbsp 
<blockquote><details><summary> Data Collection Pipelines</summary></details></blockquote>
  
<blockquote><details><summary> Data Curation and Processing Pipelines</summary></details></blockquote>

<blockquote><details><summary> Data Analysis Pipelines</summary></details></blockquote>
</details>

<details>
<summary>CT</summary>
&nbsp 
<blockquote><details><summary> Data Collection Pipelines</summary></details></blockquote>
  
<blockquote><details><summary> Data Curation and Processing Pipelines</summary></details></blockquote>

<blockquote><details><summary> Data Analysis Pipelines</summary></details></blockquote>
</details>

<details>
<summary>PET</summary>
&nbsp 
<blockquote><details><summary> Data Collection Pipelines</summary></details></blockquote>
  
<blockquote><details><summary> Data Curation and Processing Pipelines</summary></details></blockquote>

<blockquote><details><summary> Data Analysis Pipelines</summary></details></blockquote>
</details>

<details>
<summary>MEG</summary>
&nbsp 
<blockquote><details><summary> Data Collection Pipelines</summary></details></blockquote>
  
<blockquote><details><summary> Data Curation and Processing Pipelines</summary></details></blockquote>

<blockquote><details><summary> Data Analysis Pipelines</summary></details></blockquote>
</details>
