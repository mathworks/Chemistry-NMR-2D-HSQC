## 7. Mnaual Processing of 2D NMR HSQC   


Many NMR processing software have automatic phase correction algorithms, but often phase correction needs to be manually applied by the user. 
In this example we will explore manual phase correction to improve the quality of a Heteronuclear Single Quantum Coherence (HSQC) experiment. 
HSQC is a sophisticated two-dimensional NMR technique that plays a crucial role in the study of molecular structures. It is termed 'heteronuclear' because it involves interactions between two different types of nuclei, typically 1H,13C or 15N. The 'single quantum coherence' aspect refers to the quantum mechanical coherence between nuclear spins, which is central to the experiment.  
We use a HSQC spectrum, whihc is kindly provided by Prof. Ilya Kuprov, University of Southampton. Starting from the time domain we applied apodization and interactively phase corrected our entire spectra. This was done by selecting a reference peak and extracting 1D FIDs from the peak center (One for F1 and one for F2 dimensions). Then phase correction was applied interactively to select 0th and 1st order phase corrections. Once we found a good 0th and 1st order correction we applied it to the entire spectrum. 


### Usage

This code can be opened in [MATLAB® Online™](https://matlab.mathworks.com/).





