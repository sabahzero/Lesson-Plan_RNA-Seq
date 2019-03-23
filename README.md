# Practice Lesson for RNA-Seq Data Analysis [Mar 26, 2019]

## Overview and aims of today
Time Point 1 (5 min) - Identify the data, how was it produced? </br>
Time Point 2 (10 min) - Walk through the data through visualization and analysis </br>
Time Point 3 (5 min) - Interpretations of results </br>
Time Point 4 (10 min) - Additional ways of analysis, and general Q&A </br>

### Time Point 1 (5 min): Introduction, understanding RNA-Seq
Checkpoint A: What is RNA-Seq, and why use it? </br> 

RNA-Seq is a next generation sequencing (NGS) method used to inform us of changes in the transcriptome. A transcriptome being the mRNA of a given cell or organism. RNA-Seq is commonly used as a tool for identifying changes before or after treatment *in vitro* (in a test tube) or *in vivo* (directly in the organism or environment of interest). </br>
![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f3/Summary_of_RNA-Seq.svg/500px-Summary_of_RNA-Seq.svg.png)</br>
*WikiJournal of Medicine* </br></br>

Checkpoint B: What is the nature of the RNA-Seq data we are using today? </br> 

Let's scroll up to the [Data_RNA-Seq_DE-Output folder](https://github.com/sabahzero/Lesson-Plan_RNA-Seq/tree/master/Data_RNA-Seq_DE-Output) and take a look. What do we see inside? There are two .csv files of normalized counts from RNA-Seq output data. These two files represent a biological replicate for treatment of yeast *Candida albicans* strain CAY540, with specific interests in identifying up- and down- regulated genes related to biofilm formation. Today we will focus on the ntar genes. </br>
![alt text](https://ars.els-cdn.com/content/image/1-s2.0-S1286457916000095-gr2.jpg) </br>
*[Gulati and Nobile 2016, Microbes and Infection](https://www.sciencedirect.com/science/article/pii/S1286457916000095)*


### Time Point 2 (10 min): Basics, creating a bar chart and changing color schemes
For this section, were' going to switch over to code. Scary! 😱 </br>

Checkpoint C: Why is it more advantageous to utilize code for our analysis over Excel? </br>

Right now we're only working with two replicates, but imagine working with 40 or 100. How much time do you estimate it would take to walk through each of those in an Excel sheet versus running a chunk of code? Let's just say "A *lot* less time"! We can think of using code analagous to using a calculator, saving us time and energy we can then re-direct elsewhere. In a longer session, we would walk through the installation process of the platforms behind this code (Github, which you are looking at now, Jupyter and R). In the interest of time, we will be working from a previously made bioinformatics version of a 'lab notebook' found [here](https://github.com/sabahzero/Lesson-Plan_RNA-Seq/blob/master/RNA-Seq_Lesson-Plan_R.ipynb). 

### Time Point 3 (5 min): Interpreting the analysis of results, visualization vs statistics

### Time Point 4 (10 min): Discussion, Q&A 

### Contacts
Sabah Ul-Hasan ([@sabazhero](https://github.com/sabahzero)) </br>

### Acknowledgements
Thanks to PhD Student Austin Perry and the Nobile Lab for permission to use this raw data sample.
