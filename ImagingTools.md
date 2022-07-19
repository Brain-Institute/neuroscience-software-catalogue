# Ontario Brain Institute Imaging Tools

| Tool/Pipeline | Description | Requirements | Compute Location | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| Scan Aquisition Pipeline | Pipeline that checks to see if there's a scan acquisition protocol which outlines specific criteria for scans.<details><summary>License</summary>Creative Commons Attribution 3.0</details> <details><summary>References</summary>Creative Commons Attribution 3.0</details>  | N/A |Brain-CODE | All |
| [fBIRN](https://www.nitrc.org/projects/fbirn/) | Quality control for any changes in function in fMRI. Stores data in HTML file. Used for non-human/phantom data. <details><summary>License</summary>BSD and BIRN</details> | N/A | Lab | All |
| [MRIQC](https://github.com/nipreps/mriqc/tree/c57059ee82c2bf07d188dbb588407a41116a1a61) | Program run on human brain scans and structural scans to provide summary variables. Is used to track outliers and indicate any potential problems in MRI function. Stores data in sessions on SPReD. Designed originally to handle large datasets.<details><summary>License</summary>3-clause BSD</details> <details><summary>Tool Citation </summary>Esteban O, Birman D, Schaer M, Koyejo OO, Poldrack RA, Gorgolewski KJ; MRIQC: Advancing the Automatic Prediction of Image Quality in MRI from Unseen Sites; PLOS ONE 12(9):e0184661; doi:10.1371/journal.pone.0184661.</details> <details><summary>Relevant Publications</summary>Ramirez et.al., 2011, Black et.al., 2002 </details> | Large size CPU|  Brain-CODE &emsp;&emsp;&emsp;&emsp; | CAN-BIND, ONDRI |

Please select the imaging tool you'd like to look at:

<details>
<summary>MRI</summary> 

### Data Collection Pipeline
MRI data is collected and processed in the MRI scanner before undergoing data curation. 
  
### Data Curation Pipeline

<details>
<summary>CAN-BIND MRI Pipeline</summary> 
  
| Tool/Pipeline | Description | Compute Location | Requirements | License | 
| ---------------- | ----------- | --------------------------- | ----------- |----------- |
| Scan Aquisition Pipeline | Pipeline that checks to see if there's a scan acquisition protocol which outlines specific criteria for scans. | Brain-CODE | N/A | Creative Commons Attribution 3.0 |
| [fBIRN](https://www.nitrc.org/projects/fbirn/) | Quality control for any changes in function in fMRI. Stores data in HTML file. Used for non-human/phantom data. | Lab | N/A | BSD and BIRN |
| [MRIQC](https://github.com/nipreps/mriqc/tree/c57059ee82c2bf07d188dbb588407a41116a1a61) | Program run on human brain scans and structural scans to provide summary variables. Is used to track outliers and indicate any potential problems in MRI function. Stores data in sessions on SPReD. Designed originally to handle large datasets. |  Brain-CODE |Large size CPU| 3-clause BSD|
| [ANT](http://stnava.github.io/ANTs/) | Pipeline for registration to a template image (normalization) | Brain-CODE | N/A | Apache Version 2.0|
| [Free Surfer - recon-all function](https://surfer.nmr.mgh.harvard.edu/fswiki/recon-all) | Function that conduct measurements of volumetric/thickness in all brain regions and looks at volume of grey matter, white matter, CSF in the brain. Takes 20 minutes per session. All results stored in session.| Frontenac |Large size CPU| GNU General Public License Version 2.0|
</details>  
  
<details>
<summary>ONDRI MRI Pipeline</summary> 
</details>  
  
<details>
<summary>EpLink MRI Pipeline</summary> 
</details>  
  
### Data Processing Pipeline

### Data Analysis Pipeline

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
