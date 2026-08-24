# EXFOR-Entry-File
The [EXFOR Entry File](https://nds.iaea.org/nrdc/exfor-master/entry/) is an official current **snapshot** of the EXFOR library and collects the latest versions of all EXFOR entries and EXFOR/CINDA dictionary. Visit the [EXFOR Master File](https://nds.iaea.org/nrdc/exfor-master/) for the annual snapshot. 

**Download**
- download the zipped file of the current version from the [EXFOR Entry File](https://nds.iaea.org/nrdc/exfor-master/entry/) website, or
- download the full repository using the terminal command:
```
git clone https://github.com/iaea-nds/exfor-entry-file.git
```

**Directory structure**
```
    +--+--x4_dirupd.log   # update log file
       |
       +--entry 
          |                 
          +--1            # Area 1
          |  +--10001.txt   # EXFOR 10001
          |  +--10002.txt   # EXFOR 10002
          |  ...
          |
          +--2            # Area 2
          |  +--20001.txt   # EXFOR 20001
          |  ...
          |
          ...
          +--9            # Area 3
          |  +--90001.txt   # EXFOR 90001 (Dictionary)
          |
          +--a            # Area A
          ...
          +--v            # Area V
```

**Terms of Use**

 When you redistribute it in the original or another form, or use it in a publication,
- cite the EXFOR reference article ([Nucl. Data Sheets 120(2014)272](http://dx.doi.org/10.1016/j.nds.2014.07.065) [[pdf](https://arxiv.org/pdf/2002.07114.pdf)]) 

The EXFOR Entry File is distributed under the terms of the CC BY 4.0 license. It is provided to the IAEA by the [NRDC Network](https://nds.iaea.org/nrdc/), which is a network under the auspices of the IAEA. As agreed by the NRDC Network, the IAEA has the role of publication and dissemination for all the data and resources provided to it by the NRDC Network. 
