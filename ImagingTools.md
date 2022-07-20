# Ontario Brain Institute Imaging Tools

Please select the imaging tool you'd like to look at:

<details>
<summary>MRI</summary> 

### Data Collection Pipeline
MRI data is collected and processed in the MRI scanner before undergoing data curation. 
  
### Data Curation Pipeline

| Tool/Pipeline | Description | Requirements | Compute Location | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| Scan Aquisition Pipeline | Pipeline that checks to see if there's a scan acquisition protocol which outlines specific criteria for scans.<details><summary>License</summary>Creative Commons Attribution 3.0</details> | N/A |Brain-CODE | All |
| [fBIRN](https://www.nitrc.org/projects/fbirn/) | Quality control for any changes in function in fMRI. Stores data in HTML file. Used for non-human/phantom data. <details><summary>License</summary>BSD and BIRN</details> | N/A | At the lab | All |
| [MRIQC](https://github.com/nipreps/mriqc/tree/c57059ee82c2bf07d188dbb588407a41116a1a61) | Program run on human brain scans and structural scans to provide summary variables. Is used to track outliers and indicate any potential problems in MRI function. Stores data in sessions on SPReD. Designed originally to handle large datasets.<details><summary>License</summary>3-clause BSD</details> <details><summary>Tool Citation </summary>    Esteban O, Birman D, Schaer M, Koyejo OO, Poldrack RA, Gorgolewski KJ; MRIQC: Advancing the Automatic Prediction of Image Quality in MRI from Unseen Sites; PLOS ONE 12(9):e0184661; doi:[10.1371/journal.pone.0184661](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0184661).</details> <details><summary>Relevant Publications</summary>Ramirez et.al., 2011, Black et.al., 2002 </details> | Large size CPU &emsp;|  Brain-CODE &emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp;&nbsp;&nbsp; | CAN-BIND, ONDRI |
  | [ANT](http://stnava.github.io/ANTs/) | Pipeline for registration to a template image (normalization) <details><summary>License</summary>Apache Version 2.0 </details> <details><summary>Tool Citation </summary>Tustison, N. J., Cook, P. A., Klein, A., Song, G., Das, S. R., Duda, J. T., Kandel, B. M., van Strien, N., Stone, J. R., Gee, J. C., &amp; Avants, B. B. (2014). Large-scale evaluation of ants and freesurfer cortical thickness measurements. NeuroImage, 99, 166–179. [https://doi.org/10.1016/j.neuroimage.2014.05.044](https://www.sciencedirect.com/science/article/pii/S1053811914004091?via%3Dihub) </details> <details><summary>Relevant Publications</summary>To be filled </details> | N/A | Brain-CODE | CAN-BIND, ONDRI|
| [Free Surfer - recon-all function](https://surfer.nmr.mgh.harvard.edu/fswiki/recon-all) | Function that conduct measurements of volumetric/thickness in all brain regions and looks at volume of grey matter, white matter, CSF in the brain. Takes 20 minutes per session. All results stored in session. <details><summary>License</summary>GNU General Public License Version 2.0 </details> <details><summary>Tool Citation </summary> Citation will depend on what the recon-all function was used for. Citation information can be found [here](https://surfer.nmr.mgh.harvard.edu/fswiki/FreeSurferMethodsCitation).</details> <details><summary>Relevant Publications</summary>To be filled </details>| Large size CPU | Frontenac | CAN-BIND, ONDRI|
| Scan Rating Service with notification | Service which notifies researcher to rate the scan. Once done for each scan, a report is generated with the ratings of all scans. All metadata is compared against a set of known parameters and deviations are flagged. <details><summary>License</summary>Creative Commons Attribution 3.0</details> | N/A | Brain-CODE | CAN-BIND, ONDRI |
| [ICN](https://www.nitrc.org/projects/icn_atlas/) | Software that uses fMRI data to create a functional network. Was used by CAN-BIND researchers to isolates 10 different networks. <details><summary>License</summary>Creative Commons Attribution 4.0</details> <details><summary>Tool Citation </summary> Kozák, L. R., van Graan, L. A., Chaudhary, U. J., Szabó, Á. G., &amp; Lemieux, L. (2017). ICN_Atlas: Automated description and quantification of functional MRI activation patterns in the framework of Intrinsic Connectivity Networks. NeuroImage, 163, 319–341. [https://doi.org/10.1016/j.neuroimage.2017.09.014](https://doi.org/10.1016/j.neuroimage.2017.09.014) </details> <details><summary>Relevant Publications</summary>To be filled </details> | N/A | At the lab | CAN-BIND |
| [OPPNI Pipeline](https://github.com/strotherlab/oppni) | Pipeline used for fMRI pre-processing. <details><summary>License</summary>GNU General Public License Version 3.0</details> <details><summary>Tool Citation </summary> To be filled </details> <details><summary>Relevant Publications</summary>To be filled </details> | Large size CPU | Frontenac | ONDRI |
| [SABRE/Sunnybrook Imaging Processing Software](https://sabre.brainlab.ca/docs/index.html#) | Pipeline used for the identification of volumetrics in lesion data for structural MRI images. <details><summary>License</summary>GNU General Public License Version 3.0</details> <details><summary>Tool Citation </summary> To be filled </details> <details><summary>Relevant Publications</summary>To be filled </details> | N/A | At the lab | ONDRI |
| [ITK-SNAP Software](https://github.com/pyushkevich/itksnap) | Software that allows for editing and viewing of structural MRI data. <details><summary>License</summary>GNU General Public License Version 3.0</details> <details><summary>Tool Citation </summary> To be filled </details> <details><summary>Relevant Publications</summary>To be filled </details> | N/A | At the lab | ONDRI |
| [ANALYZE Software](https://analyzedirect.com) | Software used for manual editing and checking procedures of structural MRI data. <details><summary>License</summary>Not sure...</details> <details><summary>Tool Citation </summary> To be filled </details> <details><summary>Relevant Publications</summary>To be filled </details> | N/A | At the lab | ONDRI |
| [FSL - FLIRT](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FLIRT) | Tool that is used for intra and inter modal brain image registration. <details><summary>License</summary> Oxford </details> <details><summary>Tool Citation </summary> M. Jenkinson and S.M. Smith. A global optimisation method for robust affine registration of brain images. Medical Image Analysis, 5(2):143-156, 2001.</br> <br>M. Jenkinson, P.R. Bannister, J.M. Brady, and S.M. Smith. Improved optimisation for the robust and accurate linear registration and motion correction of brain images. NeuroImage, 17(2):825-841, 2002.</br> <br>Greve, D.N. and Fischl, B. Accurate and robust brain image alignment using boundary-based registration. NeuroImage, 48(1):63-72, 2009. </br> </details> <details><summary>Relevant Publications</summary>To be filled </details> | >16 GB RAM, Swap space at least equal to GB of RAM, Disk space at least 10 times the size of data sets | At the lab | ONDRI |
| [FSL - BET](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/BET) | Tool that is used to extract the intra-cranial volume for each subject by removal of the skull and infratentorial structures. <details><summary>License</summary> Oxford </details> <details><summary>Tool Citation </summary> S.M. Smith. Fast robust automated brain extraction. Human Brain Mapping, 17(3):143-155, November 2002. </br> <br>If skull and scalp surface extraction functions are also used, please also reference the following:</br> <br> M. Jenkinson, M. Pechaud, and S. Smith. BET2: MR-based estimation of brain, skull and scalp surfaces. In Eleventh Annual Meeting of the Organization for Human Brain Mapping, 2005. </details> <details><summary>Relevant Publications</summary>To be filled </details> | >16 GB RAM, Swap space at least equal to GB of RAM, Disk space at least 10 times the size of data sets | At the lab | ONDRI |
| [N3 Software](https://github.com/BIC-MNI/N3) | To be filled <details><summary>License</summary> To be filled </details> <details><summary>Tool Citation </summary> J.G. Sled, A.P. Zijdenbos and A.C. Evans, "A non-parametric method for automatic correction of intensity non-uniformity in MRI data",in "IEEE Transactions on Medical Imaging", vol. 17,  pp. 87--97, February 1998. </br> <br>J.G. Sled, "A Non-parametric Method for Automatic Correction of Intensity Non-uniformity in MRI Data", Master's Thesis, McGill University, Montreal, QC, May 1997 (available at http://www.bic.mni.mcgill.ca/~jgsled/thesis/)</br> <br> J.G. Sled, A.P. Zijdenbos and A.C. Evans, "A Comparison of Retrospective Intensity Non-uniformity Correction Methods for MRI", Information Processing in Medical Imaging, pp. 459-464, 1997 </details> <details><summary>Relevant Publications</summary>To be filled </details> | N/A | At the lab | ONDRI |
| [FSL - FAST](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FAST?highlight=%28mfast%29) (Previously mfast) | To be filled <details><summary>License</summary> Oxford </details> <details><summary>Tool Citation </summary> Zhang, Y. and Brady, M. and Smith, S. Segmentation of brain MR images through a hidden Markov random field model and the expectation-maximization algorithm. IEEE Trans Med Imag, 20(1):45-57, 2001. </details> <details><summary>Relevant Publications</summary>To be filled </details> | >16 GB RAM, Swap space at least equal to GB of RAM, Disk space at least 10 times the size of data sets | At the lab | ONDRI |
| [SPM Software](https://www.fil.ion.ucl.ac.uk/spm/) | Software that uses a thresholded probabilistic white matter template to create a white matter mask. <details><summary>License</summary>GNU General Public License Version 2.0</details> <details><summary>Tool Citation </summary> To be filled </details> <details><summary>Relevant Publications</summary>To be filled </details> | N/A | At the lab | ONDRI |
| [OSIRIX](https://www.osirix-viewer.com/) | Software used for confirmation of de-identification of MRI data by EpLink researchers. <details><summary>License</summary>to be filled</details> <details><summary>Tool Citation </summary> To be filled </details> <details><summary>Relevant Publications</summary>To be filled </details> | N/A | At the lab | EpLink |
| [MANGO](https://ric.uthscsa.edu/mango/mango.html) | Software used for confirmation of de-identification of MRI data by EpLink researchers. <details><summary>License</summary>to be filled</details> <details><summary>Tool Citation </summary> To be filled </details> <details><summary>Relevant Publications</summary>To be filled </details> | N/A | At the lab | EpLink |

### Data Processing Pipeline

### Data Analysis Pipeline

| Tool/Pipeline | Description | Requirements | Compute Location | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| RStudio | Used for data visualization for structural MRI data | N/A | At the lab | ONDRI |
| MATLAB | Used for data visualization for structural MRI data | N/A | At the lab | ONDRI |
| SPSS | Used for testing of hypotheses by ONDRI resarchers | N/A | At the lab | ONDRI |

</details>

<details>
<summary>EEG</summary>

### Data Collection Pipeline
 
### Data Curation Pipeline

| Tool/Pipeline | Description |Research Program(s)| Compute Location | Requirements | License | 
| ---------------- | ----------- | --------------------------- | ----------- |----------- |----------- |
| [EEGLAB](https://sccn.ucsd.edu/eeglab/index.php) | Tool that is used for conversion of EEG data into EDF format, normalization and standardization of EEG data. |CAN-BIND| Lab | MATLAB, > 8 GB and multi-core 64-bit processors recommended for large datasets | MIT License |
| [ERPEEG](https://github.com/EEGSignalProcessing/ERPEEG/releases/tag/v2.0) | Tool that is used for streamlined processing of ERP data |CAN-BIND| Lab | MATLAB | GNU General Public License Version 3.0 |
| [DATA2BIDS](https://github.com/SIMEXP/Data2Bids) | includes steps from acquisition to conversion to EDF and packaging to BIDS |EpLink| Brain-CODE | N/A | MIT License |
  
### Data Processing Pipeline

### Data Analysis Pipeline
</details>

<details>
<summary>DTI</summary>

### Data Collection Pipeline
  
### Data Curation Pipeline
| Tool/Pipeline | Description | Requirements | Compute Location | Additional Information | 
| ---------------- | --------------------------------- | --------------------------- | --------------------------- | --------------------------- | 
| DTI tractographer (TBSS part of FSL) | Tool that is used to improve the clarity of DTI results. | N/A | Lab|<details><summary>Research Program(s)</summary> ONDRI </details><details><summary>License</summary>FSL License</details>|

### Data Processing Pipeline

### Data Analysis Pipeline
</details>

<details>
<summary>TMS</summary>

### Data Collection Pipeline
  
### Data Curation Pipeline

### Data Processing Pipeline

### Data Analysis Pipeline
</details>

<details>
<summary>CT</summary>

### Data Collection Pipeline
  
### Data Curation Pipeline

### Data Processing Pipeline

### Data Analysis Pipeline
</details>

<details>
<summary>PET</summary>

### Data Collection Pipeline
  
### Data Curation Pipeline

### Data Processing Pipeline

### Data Analysis Pipeline
</details>

<details>
<summary>MEG</summary>

### Data Collection Pipeline
  
### Data Curation Pipeline

### Data Processing Pipeline

### Data Analysis Pipeline
</details>

All imaging tools can be found at the excel spreadsheet here: insert link to spreadsheet...
