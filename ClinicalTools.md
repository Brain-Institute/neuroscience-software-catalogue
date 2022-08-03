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
| [RStudio](https://www.rstudio.com/) | Software that is used to write R scripts which are subsequently used to analyze clinical datasets. | N/A | At the lab |CAN-BIND, ONDRI, CP-NET, POND &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
| [MATLAB](https://www.mathworks.com/products/matlab.html) | Software that is used to write scripts which are subsequently used to analyze clinical datasets. | N/A | At the lab |ONDRI, CP-NET |
| [Python](https://www.python.org/) | Programming language used to write scripts to analyze clinical datasets. | N/A | At the lab |ONDRI, CP-NET|
| [SPSS](https://www.ibm.com/products/spss-statistics?utm_content=SRCWW&p1=Search&p4=43700050715561164&p5=e&gclid=EAIaIQobChMIt-eJ2_Wo-QIV2vvjBx1mQwE9EAAYASAAEgJ0vfD_BwE&gclsrc=aw.ds) | Software suite used for data analysis of clinical datasets. | N/A | At the lab |ONDRI, CP-NET, EpLink|
| [SASS](https://sass-lang.com/) | CSS language extension used for data analysis of clinical datasets. | N/A | At the lab |ONDRI, CP-NET|
| [NVIVO](https://www.qsrinternational.com/nvivo-qualitative-data-analysis-software/home) | Software used to conduct thematic analysis on qualitative datasets. | N/A | At the lab |CP-NET|
| [JMP](https://www.jmp.com/en_ca/offers/jmp-free-trial.html?utm_term=jmp&utm_campaign=(JMP)+Amer+-+CAN+-+ENG+-+Search+-+Branded&utm_source=adwords&utm_medium=ppc&hsa_acc=9962611730&hsa_cam=15955150013&hsa_grp=133915103193&hsa_ad=576168617756&hsa_src=g&hsa_tgt=kwd-169702162&hsa_kw=jmp&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gclid=EAIaIQobChMIlPD_6vWo-QIVj-DICh1VagyLEAAYASAAEgIM9_D_BwE) | Statistical software used to conduct statistical analysis. | N/A | At the lab |POND|
  
</details>

<details><summary>Clinical Coding Packages</summary>
&nbsp

| Package Name | Description | Coding Language | Research Program(s) |
| ---------------- | ----------- | --------------------------- | ---------|
| [Tidyverse](https://tidyverse.tidyverse.org/) |Set of packages that allow for efficient installation and use of packages from the tidyverse. <details><summary>License</summary>MIT License</details><details><summary>Tool Citation(s)</summary>Wickham H, Averick M, Bryan J, Chang W, McGowan LD, François R, Grolemund G, Hayes A, Henry L, Hester J, Kuhn M, Pedersen TL, Miller E, Bache SM, Müller K, Ooms J, Robinson D, Seidel DP, Spinu V, Takahashi K, Vaughan D, Wilke C, Woo K, Yutani H (2019). “Welcome to the tidyverse.” Journal of Open Source Software, 4(43), 1686. doi:10.21105/joss.01686.</details> | R | CAN-BIND, ONDRI |
| [dplyr](https://dplyr.tidyverse.org/) | Package that consists of a set of functions that solve the most common data manipulations. <details><summary>License</summary>MIT License</details> <details><summary>Tool Citation(s)</summary>Wickham H, François R, Henry L, Müller K (2022). dplyr: A Grammar of Data Manipulation. https://dplyr.tidyverse.org, https://github.com/tidyverse/dplyr.</details>| R | CAN-BIND, ONDRI |
| [Haven](https://haven.tidyverse.org/) | Package that allows for the reading and writing of various data formats used by other statistical packages in R. <details><summary>License</summary>MIT License</details> <details><summary>Tool Citation(s)</summary>Wickham H, Miller E, Smith D (2022). haven: Import and Export 'SPSS', 'Stata' and 'SAS' Files. https://haven.tidyverse.org, https://github.com/tidyverse/haven, https://github.com/WizardMac/ReadStat.</details>| R | CAN-BIND |
| [stringr](https://stringr.tidyverse.org/) | Package that allows for easier manipulation of strings in R. <details><summary>License</summary>GNU General Public License Version 2 </details> <details><summary>Tool Citation(s)</summary>Wickham H (2022). stringr: Simple, Consistent Wrappers for Common String Operations. http://stringr.tidyverse.org, https://github.com/tidyverse/stringr.</details>| R | ONDRI |
| [lubridate](https://lubridate.tidyverse.org/) | Package that allows for easier use of date and time in R. <details><summary>License</summary>GNU General Public License Version 2 </details> <details><summary>Tool Citation(s)</summary>Garrett Grolemund, Hadley Wickham (2011). Dates and Times Made Easy with lubridate. Journal of Statistical Software, 40(3), 1-25. URL https://www.jstatsoft.org/v40/i03/.</details> | R | ONDRI |
| [varhandle](https://bitbucket.org/mehrad_mahmoudian/varhandle/wiki/Home) | Package that allows for easier, faster, and safer handling of variables in R. <details><summary>License</summary>GNU General Public License Version 2 </details> <details><summary>Tool Citation(s)</summary>Mehrad Mahmoudian (2020). varhandle: Functions for Robust Variable Handling. R package version 2.0.5. https://CRAN.R-project.org/package=varhandle.</details> | R | ONDRI |
| [readr](https://readr.tidyverse.org/) | Package that allows for efficient reading of rectangular data from delimited files such as comma-separated values (CSV) and tab-separated values (TSV). <details><summary>License</summary>MIT License</details> <details><summary>Tool Citation(s)</summary>Wickham H, Hester J, Bryan J (2022). readr: Read Rectangular Text Data. https://readr.tidyverse.org, https://github.com/tidyverse/readr.</details> | R | ONDRI |
| [tidyr](https://tidyr.tidyverse.org/) | Package that allows for tidying of data in R. <details><summary>License</summary>MIT License</details> <details><summary>Tool Citation(s)</summary>Wickham H, Girlich M (2022). tidyr: Tidy Messy Data. https://tidyr.tidyverse.org, https://github.com/tidyverse/tidyr.</details> | R | ONDRI |
| knitr | ----------- | R | ONDRI |
| abind | ----------- | R | ONDRI |
| pandas | ----------- | Python | CP-NET |
| matplotlib/seaborn | ----------- | Python | CP-NET |

</details>
