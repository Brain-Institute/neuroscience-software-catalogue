# Ontario Brain Institute Wearable Tools

**Data Curation and Processing Pipelines**
&nbsp;  
| Tool/Pipeline | Description | Requirements | Compute Location | Research Area(s) |
| ---------------- | ----------- | --------------------------- | ----------- | ---------|
| [RStudio](https://www.rstudio.com/) | Software used to write R scripts to wrangle wearables data, | N/A | At the lab | Depression |
| [Nimbalwear](https://github.com/nimbal) (to be released!) | Python package that is used for wearables data curation and analysis. Will be able to run 6 different pipelines: <br> <blockquote><details><summary>Organization Pipeline</summary>Pipeline used to organize wearables data before processing. </details></blockquote> <blockquote><details><summary> Conversion Pipeline</summary> Pipeline that converts compressed binary files into standardized European Data Format (EDF). </details></blockquote> <blockquote><details><summary>Synchronization Pipeline</summary>Pipeline that synchronizes data based on known movements (including naturalistic movements) </details></blockquote> <blockquote><details><summary>Event Detection Pipeline</summary>Pipeline that detects bouts of sleep, walking, non-wear events and other events. </details></blockquote> <blockquote><details><summary>Feature Extraction Pipeline</summary>Pipeline that extracts features of bouts (length/duration, frequency, macrolevel, stride, step times).</details> </blockquote> <blockquote><details><summary>Analysis Pipeline</summary>Pipeline that performs analysis on wearables data. </details></blockquote> | Python, [Numpy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), [scipy](https://scipy.org/) | At the lab | Neurodegeneration |


