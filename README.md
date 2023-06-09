﻿# Optical Spectrum Analyzer (OSA) And Optical Power Meter (OPM) Design 📈📡🧮

## Project Overview

Fiber optic networks use pulses of light to transmit digital information over long distances. Compared to traditional copper wire networks, fiber optic networks have several advantages, including higher bandwidth, faster data transmission rates, and better resistance to electromagnetic interference.

WDM (Wavelength Division Multiplexing) technology is often used in fiber optic networks to increase their capacity. WDM allows multiple streams of data to be transmitted over a single fiber by separating the different wavelengths of light used to transmit the data. This enables multiple signals to be transmitted simultaneously over the same fiber, increasing the overall capacity and efficiency of the network.

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Wavelength Division Multiplexing.png" alt="icon"/>
            </a>
          <br><small><i>Figure 1 : Wavelength Division Multiplexing</i></small>
        </td>  
    </tr>
</table>

High-speed data transmission is another key feature of fiber optic networks. The high bandwidth of fiber optic cables allows for faster data transmission rates than traditional copper wire networks, making fiber optic networks ideal for applications such as streaming video, online gaming, and cloud computing.

### Introduction of Optical Spectrum Analyzer

An Optical Spectrum Analyzer (OSA) is an important tool in the field of optical communication that is used to measure and display the ```distribution of power``` of an optical source over a ```specified wavelength span```. 

> Observations :

- The spectral characteristics of an optical signal, including its center ```wavelength```, ```bandwidth```, and ```power levels``` at different wavelengths.
- Channel Failure
- OSNR 
- Channel Separation

> OSAs are used in a variety of applications, including:

- Fiber optic communications
- Laser characterization
- Spectroscopy
- They are especially useful in the design and testing of optical components, such as fiber Bragg gratings and optical filters, as well as in the troubleshooting of optical systems.

### Problem Statements

> Diagnosed the Problems 1: 

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Analysis 1.png" alt="icon"/>
            </a>
          <br><small><i>Figure 2 : Analysis 1</i></small>
        </td>  
    </tr>
</table>


> Diagnosed the Problems 2: 

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Analysis 2.png" alt="icon"/>
            </a>
          <br><small><i>Figure 3 : Analysis 2</i></small>
        </td>  
    </tr>
</table>


## Project Scope

One of the scope of this project is to design a ```Filter Control Program``` that can communicate with the optical tunable filter using GPIB interface and plot the optical spectrum within the C & L band using LabVIEW. 

```LabVIEW Programming``` ```Instrument Controlling``` ```Insertion Loss of filter (IL)```


> The program should be able to perform the following tasks:

- Establish communication between the computer and the optical tunable filter via GPIB interface. 

- Control the parameters of the optical tunable filter such as wavelength, bandwidth, and attenuation. 

- Retrieve the optical spectrum data from the optical tunable filter. 

- Process the optical spectrum data to remove noise and other unwanted signals. 

- Plot the processed optical spectrum data using LabVIEW within the C & L band. 

- The project aims to provide a user-friendly and efficient way to control the optical tunable filter and visualize the optical spectrum within the C & L band using LabVIEW. 

<br>

Another scope of this project is to design an ```Optical Power Meter``` that can detect peak powers when the optical filter is varying with the wavelength or frequency within the C & L band. 

```TIA Circuit``` ```P (nm) vs V (A)``` ```P (nm) , V (A), IL```

> The project should be able to perform the following tasks:

- Detect the power of the incoming optical signal within the C & L band.

- Detect the peak power of the optical signal as the optical filter varies with wavelength or frequency.

- Display the peak power values on a graphical user interface.

- Allow the user to select the wavelength or frequency range to monitor and display the corresponding peak power values.

- Provide the ability to save and export the peak power values for further analysis.

- The project aims to provide a reliable and accurate way to monitor and measure peak powers within the C & L band as the optical filter varies with wavelength or frequency. 


## Project Prototypes

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Enclosure Design 1.png" alt="icon"/>
            </a>
          <br><small><i>Figure 4 : Enclosure Design OPM Version 1</i></small>
        </td>  
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Enclosure Design 2.png" alt="icon"/>
            </a>
          <br><small><i>Figure 5 : Enclosure Design for OPM Version 2</i></small>
        </td> 
    </tr>
</table>


## Project Achievements Beyond the Scope

- Accomplished the ```0.13 nm``` resolution by cascading the two JDSU TB9 optical grating filter via GPIB interface.

- Designed LabVIEW program for acquiring optical power measurements from Agilent Lightwave Power sensor via GPIB interface. 

- Improved the LabVIEW user interface.

- Designed the portable device for the optical power meter circuit (3D Printing).


## Observation : 

> Within the Scope :

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Project Setup for Design 1 .png" alt="icon"/>
            </a>
          <br><small><i>Figure 6 : Actual setup of the OpticaSa Spectrum Analyzer Design 1 </i></small>
        </td>  
    </tr>
</table>

> Beyond the Scope :

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Project Setup for Design 2.png" alt="icon"/>
            </a>
          <br><small><i>Figure 7 : Actual setup of the OpticaSa Spectrum Analyzer Design 2 </i></small>
        </td>  
    </tr>
</table>


### Data Visualization :

> Within the Scope : 

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="DA 1.png" alt="icon"/>
            </a>
          <br><small><i>Figure 9 : Final Outcome (GUI DESIGN) of the Project Prototype Design Version 1 using LabView Program </i></small>
        </td>  
    </tr>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="DA 2.png" alt="icon"/>
            </a>
          <br><small><i>Figure 10 : Optical Spectrum on the JDSU MTS 6000A OSA and Agilent Network Analyzer </i></small>
        </td>  
    </tr>
</table>


> Beyond the Scope : 

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="DA 3.png" alt="icon"/>
            </a>
          <br><small><i>Figure 11 : (GUI DESIGN) Optical Spectrum Using Portable Power Meter (version 2) at Cascading Two TB9 Optical Filters </i></small>
        </td>  
    </tr>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="DA 4.png" alt="icon"/>
            </a>
          <br><small><i>Figure 12 : Optical Spectrum on the JDSU T-BRED 6000A OSA </i></small>
        </td>  
    </tr>
</table>


### Comparison Between the OPM Versions and OSAs

> Comparison between the Project Prototype Versions, exiting 81634A power Sensor and Existing OSA :

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Comparison.png" alt="icon"/>
            </a>
          <br><small><i>Figure 8 : Comparison between the Project Prototype Versions </i></small>
        </td>  
    </tr>
</table>



## Tech Stack  
<table>
        <td align="center" width="96">
            <a href="#macropower-tech">
                <img src="https://upload.wikimedia.org/wikipedia/commons/4/43/National_Instruments_logo_2020.svg" alt="icon" width="65" height="65" />
            </a>
            <br>NI
        </td>
        <td align="center" width="96">
            <a href="#macropower-tech">
                <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="icon" width="65" height="65" />
            </a>
            <br>Arduino
        </td>
        <td align="center" width="96">
            <img src="https://camo.githubusercontent.com/98a9974ff054d224f6af9afce36893b66a9389af2ee67bb54b2b10ae66ff0de4/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6c6162766965772f6c6162766965772d6f726967696e616c2d776f72646d61726b2e737667" width="65" height="65" />
          <br>LabView
        </td>
        <td align="center" width="96">
        <a href="#macropower-tech">
                <img src="https://raw.githubusercontent.com/github/explore/7af95003139e68a3a54e382bb4f23a72836ef348/topics/altium-designer/altium-designer.png" alt="excel" width="65" height="65" />
            </a>
            <br> Altium
        </td>
        <td align="center" width="96">
            <a href="#macropower-tech">
                <img src="https://cdn.freebiesupply.com/logos/large/2x/solidworks-logo-png-transparent.png" alt="excel" width="65" height="65" />
            </a>
            <br> SolidWorks
        </td>
        <td align="center" width="96">
            <a href="#macropower-tech">
                <img src="https://upload.wikimedia.org/wikipedia/commons/3/34/Microsoft_Office_Excel_%282019%E2%80%93present%29.svg" alt="excel" width="65" height="65" />
            </a>
            <br>Excel
        </td>
        <td align="center" width="96">
            <a href="#macropower-tech">
                <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="65" height="65" />
            </a>
            <br>Git
        </td>
        <td align="center" width="96">
            <a href="#macropower-tech">
                <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="65" height="65" />
            </a>
            <br>Illustrator
        </td>
</table>


## Authors

- [@SasanthaR](https://github.com/SasanthaR) | [Sasantha Roshana](https://www.linkedin.com/in/sasantha-roshana-62568a18b/?originalSubdomain=lk)


<br>
<i>Associated With:</i> 

- Faculty of Engineering: [SLTC Research University | LK](https://sltc.ac.lk/) 
- Under Supervision: [Dr.Sumudu Edirisinghe](https://www.linkedin.com/in/sumudu-edirisinghe-7aa3132/?originalSubdomain=uk/) 


## Suggestions ✨🤝 

Don't forget to leave feedback if you find this repo useful or any improvements. ⭐🌹🥧

Thank you 🧡



