# Ontario Brain Institute Clinical Tools

<details><summary>Data Collection Pipelines</summary>
&nbsp

| Tool/Pipeline | Description | Requirements | Compute Location | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| [REDCap](https://www.project-redcap.org/) | Online survey conduction and collection | N/A | [Brain-CODE](https://www.braincode.ca/) |CP-NET, EPLINK, CAN-BIND, ONDRI, CONNECT|
| [Medidata Rave](https://www.medidata.com/en/clinical-trial-products/clinical-data-management/edc-systems/) | Data is scored entering into the system. Cloud based clinical data management system used for electornic data capture. Flags errors.| N/A | At AHRC |POND|

</details>

<details><summary>Data Curation and Processing Pipelines</summary>
&nbsp

| Tool/Pipeline | Description | Requirements | Compute Location | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| [RStudio](https://www.rstudio.com/) | Software used to write R scripts which are subsequently used to wrangle data. | N/A | At the lab |CAN-BIND|
| [RStudio](https://www.rstudio.com/) | Software used to write R scripts that conduct 3 main functions <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1. Directly reading data from REDCap using an API &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; token. <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2. Quality control of REDCap data by examining &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;missing-ness (missing-ness/date-range issues) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;and correcting any issues. <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3. Comparing computer scaled scores to &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;coordinator entered scaled scores to evaluate &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;human error. | N/A | [Brain-CODE](https://www.braincode.ca/) |ONDRI|
| [Data Preparation (Shiny) App](https://github.com/ondri-nibs/dataprep_app) | Prepares ONDRI data for outlier analysis. <details><summary>License</summary>GNU General Public License Version 3.0</details> | R, RStudio, [GSVD](https://github.com/derekbeaton/GSVD) and [ours](https://github.com/derekbeaton/OuRS) R Packages | At the lab | ONDRI| 
| [Outliers (Shiny) App](https://github.com/ondri-nibs/outliers_app) | Performs outlier analyses on ONDRI data <details><summary>License</summary>GNU General Public License Version 3.2</details> | R, Rstudio | At the lab | ONDRI| 
| [REDCap](https://www.project-redcap.org/) | Online software used to conduct quality control and quality assurance on clinical data. | N/A | [Brain-CODE](https://www.braincode.ca/) |EpLink, CP-NET &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
| [Python](https://www.python.org/) | Language used to write scripts that conduct quality control checks, quality assurance checks, and generation of monthly progress reports. | N/A | [Brain-CODE](https://www.braincode.ca/) |CP-NET|

</details>
  
<details><summary>Data Analysis Pipelines</summary>
&nbsp

| Tool/Pipeline | Description | Requirements | Compute Location | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| [RStudio](https://www.rstudio.com/) | Online survey conduction and collection | N/A | At the lab |CAN-BIND, ONDRI, CP-NET, POND|
| [MATLAB](https://www.mathworks.com/products/matlab.html) | Online survey conduction and collection | N/A | At the lab |ONDRI, CP-NET|
| [Python](https://www.python.org/) | Online survey conduction and collection | N/A | At the lab |ONDRI, CP-NET|
| [SPSS](https://www.ibm.com/products/spss-statistics?utm_content=SRCWW&p1=Search&p4=43700050715561164&p5=e&gclid=EAIaIQobChMIt-eJ2_Wo-QIV2vvjBx1mQwE9EAAYASAAEgJ0vfD_BwE&gclsrc=aw.ds) | Online survey conduction and collection | N/A | At the lab |ONDRI, CP-NET|
| [SASS](https://sass-lang.com/) | Online survey conduction and collection | N/A | At the lab |ONDRI, CP-NET|
| [NVIVO](https://www.qsrinternational.com/nvivo-qualitative-data-analysis-software/home) | Online survey conduction and collection | N/A | At the lab |ONDRI, CP-NET|
| [JMP](https://www.jmp.com/en_ca/offers/jmp-free-trial.html?utm_term=jmp&utm_campaign=(JMP)+Amer+-+CAN+-+ENG+-+Search+-+Branded&utm_source=adwords&utm_medium=ppc&hsa_acc=9962611730&hsa_cam=15955150013&hsa_grp=133915103193&hsa_ad=576168617756&hsa_src=g&hsa_tgt=kwd-169702162&hsa_kw=jmp&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gclid=EAIaIQobChMIlPD_6vWo-QIVj-DICh1VagyLEAAYASAAEgIM9_D_BwE) | Online survey conduction and collection | N/A | At the lab |POND|
  
</details>

<details><summary>Clinical Coding Packages</summary>
&nbsp

| Package Name | Description | Coding Language | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ---------|
| Tidyverse | ----------- | R | CAN-BIND, ONDRI |
| dplyr | ----------- | R | CAN-BIND, ONDRI |
| Haven | ----------- | R | CAN-BIND |
| stringr | ----------- | R | ONDRI |
| lubridate | ----------- | R | ONDRI |
| varhandle | ----------- | R | ONDRI |
| readr | ----------- | R | ONDRI |
| DT | ----------- | R | ONDRI |
| tidyr | ----------- | R | ONDRI |
| knitr | ----------- | R | ONDRI |
| abind | ----------- | R | ONDRI |
| pandas | ----------- | Python | CP-NET |
| matplotlib/seaborn | ----------- | Python | CP-NET |

</details>
