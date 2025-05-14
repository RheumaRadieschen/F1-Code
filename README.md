Sometimes I think but then I forget
This here is a small introduction for the README file. I should explain what I am doing but honestly.... I dont even know myself what I am doing here. I scammed myself through whole life and now I sit here and to make the best out of it. It.... is.... fabulous!!!!

In this F1-internship at the CCTB I will work trough the "onboarding - base module" which is accessible over Github. 
It was created to guid new students trough a realistic project (short project). With the help of this guide I should be able to analyze an in-situ sequencing dataset by using the python programming language. 
The workflow consists of alternating steps of work on the project, which is writing and executing code mostly, but also documentation. After each hopefully logical step, the progress is committed to version control. 

## Data Information

### What is the data?
The data used in this project is related to in-situ sequencing datasets. These datasets contain sequences of DNA or RNA that have been captured and recorded in their original location within a biological sample.

### What files are used?
The data is stored in the `data` directory and includes the following files:
- `data/raw_data.csv`: Contains the raw sequencing data.
- `data/processed_data.csv`: Contains the processed and cleaned sequencing data.
- `data/metadata.csv`: Contains metadata information about the samples, such as sample ID, collection date, and other relevant details.

### What does the data mean?
- **raw_data.csv**: This file includes the initial sequencing reads obtained directly from the sequencing machine. Each row represents a single read with various attributes such as sequence ID, nucleotide sequence, quality scores, etc.
- **processed_data.csv**: This file contains the cleaned and processed sequencing data. The processing steps may include filtering out low-quality reads, trimming adapter sequences, and aligning reads to a reference genome.
- **metadata.csv**: This file provides additional context for the sequencing data. It includes information about each sample, such as the sample ID, the date it was collected, the type of tissue or cell it was obtained from, and any other relevant experimental conditions.

This data is crucial for analyzing and understanding the biological processes at a molecular level, and it will be used throughout the project to perform various analyses and generate insights.