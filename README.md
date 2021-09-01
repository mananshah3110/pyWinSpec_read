# pyWinSpec_read
Read data directly from .spe files created by princeton WinSpec.

Converting .spe files into ASCII/text files loses its metadata such as detector temperature, integration time, binning, step and glue, etc. Therefore, it is better to directly read the data from the source file itself for further analysis without relying on hand-written notes (of experimental parameters) especially when the overall data size is in GBs.

This notebook tries to read the detecor parameters (mentioned above) and also the experimental paramenters (such as laser power, laser wavelength, sample temerature, etc. from a filename). It forces the user to follow a filenaming convention so that all the necessary paramenters are accounted for meticulous analysis of scientific data afterwards.

In addition, a small effort has been put into to prepare publication quality figures using matplotlib and also in data analysis. Feel free to extend data analysis part further alongwith other useful application as per your need.
