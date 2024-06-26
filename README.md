Data for Figures shown in Gonzalez-Islas et al 2024 eLife study "GABAergic synaptic scaling is triggered by changes in spiking activity rather than AMPA receptor activation". Also included is the burst detection program used to do the spiking analysis.

Burst Detection App (BurstDetection_V3.mlapp) for identifying bursts. Program was based on the following study:
Bakkum DJ, Radivojevic M, Frey U, Franke F, Hierlemann A, Takahashi H. Parameters for burst detection. Front Comput Neurosci. 2014 Jan 13;7:193. doi: 10.3389/fncom.2013.00193. PMID: 24567714; PMCID: PMC3915237.

Directions for Burst detection program: In order to load the matlab file for analysis push the select button on the right of the opening tab and navigate to the file on your computer that you want to analyze and select it. Then hit the Run button and the full file is displayed from start to end (this can also be limited to a smaller portion of the file (using the Start and End times). Further, you can select which channels are used for burst detection (the channels that you don’t use for burst detection can still contribute to the results). In the burst detection tab you choose the minimum number of spikes within a burst, the minimum number of channels within a burst, and the time window that the chosen number of spikes must occur within. You then Run the analysis program and can Save the results to an excel file.
