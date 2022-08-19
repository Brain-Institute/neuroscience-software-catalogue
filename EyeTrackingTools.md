# Ontario Brain Institute Eye-Tracking Tools

For a comprehensive guide on how all the tools below fit into an eye-tracking pipeline, please see [here](https://www.biorxiv.org/content/10.1101/2022.02.22.481518v1.full). 

**Data Collection Pipelines**

| Tool/Pipeline | Description | Requirements | Compute Location | Research Area(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| [EyeLink](https://www.sr-research.com/software/) | Collects eye-tracking data and stores data in proprietary binary files (EyeLink specific format). <details><summary>License</summary>Software License</details> | N/A | At the lab | Neurodegeneration |
| Lab made Java Code | Converts EyeLink data into MATLAB fIles | N/A | At the lab | Neurodegeneration |
| [MATLAB](https://www.mathworks.com/products/matlab.html) | MATLAB eye-tracking files were combined with their paired metadata text file. | N/A | At the lab | Neurodegeneration |
| [MATLAB filtfilt function](https://www.mathworks.com/help/signal/ref/filtfilt.html)| MATLAB function that conducts zero-phase digital filtering of eye-tracking data by processing the MATLAB data in both forward and reverse directions. | MATLAB | At the lab | Neurodegeneration |

**Data Curation and Processing Pipelines**
  
| Tool/Pipeline | Description | Requirements | Compute Location | Research Area(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| [MATLAB](https://www.mathworks.com/products/matlab.html) | MATLAB was used for all processing of eye-tracking data described in the steps below: <br> <blockquote><details><summary>Blink detection and definition</summary>Processing done to detect whether blinks were true blinks or another form of loss. Blink data was curated into a chart in which the data could be classified by the experimentor. </details></blockquote>  <blockquote><details><summary>Saccade detection and definition</summary>Processing that takes into account the fluid dynamics, rotational acceleration, and slosh of the eye to track the path of the saccade. </details></blockquote> <blockquote><details><summary>Saccade Table</summary> Creation of a table summarizing the information in each saccade, outlining information such as trial, start and end point, peak velocity, acceleration, amplitude, angle, and duration. </details></blockquote> The following processes are done specifically for eye-tracking data obtained during the Interleaved Pro- and Anti-Saccade Task (IPAST). <blockquote><details><summary>Pupillometry</summary>Analysis of pupil size done during FIX and GAP periods and only when the pupil was stationary. Measurements of pupil constriction and dilation at baseline were also calculated. </details></blockquote> <blockquote><details><summary>IPAST Saccade Classification</summary>Saccades were classified based on when they occured and their start and end positions.</details></blockquote> <blockquote><details><summary>IPAST Trial Classification</summary>Trials in the IPAST were classified into one of the many types of trials displayed [here](https://www.biorxiv.org/content/biorxiv/early/2022/02/25/2022.02.22.481518/T1.medium.gif).</details></blockquote>| N/A | At the lab | Neurodegeneration |
