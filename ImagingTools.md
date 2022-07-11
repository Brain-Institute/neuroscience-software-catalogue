# Ontario Brain Institute Imaging Tools

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
| [fBIRN](https://www.nitrc.org/projects/fbirn/) | Quality control for any changes in function in fMRI. Stores data in HTML file. Used for non-human/phantom data. | At the lab | N/A | BSD and BIRN |
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

| Tool/Pipeline | Description | Compute Location | Requirements | License | 
| ---------------- | ----------- | --------------------------- | ----------- |----------- |
| Scan Aquisition Pipeline | Pipeline that checks to see if there's a scan acquisition protocol which outlines specific criteria for scans. | Brain-CODE | N/A | Creative Commons Attribution 3.0 |
| fBIRN | Quality control for any changes in function in fMRI. Stores data in HTML file. Used for non-human/phantom data. | At the lab | N/A | BSD and BIRN |
| [MRIQC](https://github.com/nipreps/mriqc/tree/c57059ee82c2bf07d188dbb588407a41116a1a61) | Program run on human brain scans and structural scans to provide summary variables. Is used to track outliers and indicate any potential problems in MRI function. Stores data in sessions on SPReD. Designed originally to handle large datasets. |  Brain-CODE |Large size CPU| 3-clause BSD|
| [ANT](http://stnava.github.io/ANTs/) | Pipeline for registration to a template image (normalization) | Brain-CODE | N/A | Apache Version 2.0|
| [Free Surfer - recon-all function](https://surfer.nmr.mgh.harvard.edu/fswiki/recon-all) | Function that conduct measurements of volumetric/thickness in all brain regions and looks at volume of grey matter, white matter, CSF in the brain. Takes 20 minutes per session. All results stored in session.| Frontenac |Large size CPU| GNU General Public License Version 2.0|
  
### Data Processing Pipeline

### Data Analysis Pipeline
</details>

<details>
<summary>DTI</summary>

### Data Collection Pipeline
  
### Data Curation Pipeline

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
