# portfolio
Examples of code I have written


This directory provides select examples of code I have written in the last few years.

+ **SAC**  
Earthquake signals recorded by seismic monitoring stations are frequently made available in so called SAC format, requiring the use of Seismic Analysis Code (SAC) for their handling. Using RAW seismic data from stations operated during a recent earthquake, this work shows code routines for reading, treating, plotting and exporting suitably processed SAC signals and could be easily modified to handle additional settings (station number, filtering, different earthquakes).
  

+ **Seismic_records**   
    In this project, pre-processed SAC signals are read into R code in order to extract common engineering earthquake parameters such as PGA and PGV or to derive more complex parameter such as spectral accelerations over a range of structural periods and Arias intensity, with relevant plots illustrating the entire sequence.
    This routine can directly follow from the SAC-based codes presented in directory /SAC, or be applied to other SAC files.


+ **NDSHA**
  In this project, synthetic earthquake seismograms generated by the NDSHA methology are read into and processed using R code, in order to extract and derive selected earthquake engineering parameters. The code shows how to incorporate the large dataset generated by the NDSHA by means of a tree structure that allows to keep track of the several relevant simulation settings and parameters.


+ kriging
    Using earthquake acceleration data defined at the nodes of a regularly-spaced grid covering the United Kingdom, this project shows the steps leading to smoothing of said data over the land by means of kriging technique. The purpose is to obtain a higher resolution national hazard map covering the entire territory.
    

  