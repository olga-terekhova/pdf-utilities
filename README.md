# pdf-utilities


## Purpose

From time to time I need to manipulate PDF files for personal use: split, merge, rotate, compress.  
It's not something that warrants the use of specialized software, but I also don't want to use free online tools because of concerns about privacy, security, and added watermarks.  
A lot of stuff can be done with Python, so I used to run small scripts in the Python IDE on my desktop.  
I currently explore using Google Colab for this: I can use Python, it's free, there's runtime with enough RAM and disk storage, and I can share the notebook so that others could easily use it too.  
I want to collect here useful scripts for editing PDFs in Colab.

### Copy PDFs  
Copies a PDF file into a new PDF file according to a user-defined list of selected pages.  
May be used to extract, drop, repeat, reorder pages.   
(1 PDF -> 1 PDF)  

### Merge PDFs  
Merges several PDFs into one PDF file (input files are sorted in an alphabetical order for merging).  
(Many PDFs -> 1 PDF)  

### Rotate PDF
Rotates pages in a PDF file in a chosen direction.  
(1 PDF -> 1 PDF)  

### Split PDFs  
Splits a PDF file into several output PDF files.  
(1 PDF -> Many PDFs)  

### Pdf to Spreads  
Converts a PDF file with one page per spread (optimized for printing) into a PDF file with two pages per spread (optimized for reading on a widescreen). 

## How to use

Simply open it in Google Colab, create a copy, and follow instructions in the notebook. 
