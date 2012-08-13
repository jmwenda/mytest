PDFPy
=====
Author: Jude Mwenda
url: http://africangeogeek.com 

Python tool box to liberate PDFs. This has been paid for courtesy of the code4Kenya initiative.
Please any issues list them on the github issues list

How to Use
==========
Now for now, what happends is one needs to use PDFMiner to get the xml file,This generates and xml document
      pdf2txt.py -o dump.xml -t xml -p 6 /home/jude/Downloads/econ2011minister.pdf 
Then run the pdf2csv.py which consumes the xml and writes a csv file for you, the only param for now is the 
file path
