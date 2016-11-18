# email_scrapper

### This script scrapes emails from a .txt file.

I use it to scrape emails from PDFs and use them for marketing. Before using this script, I perform following steps:

1. Download all the relevant PDFs, which have the required emails

2. Convert all the PDFs into a single text file using ant opensource or hosted software

3. Use this script to parse emails from the text file.

_I have used re and csv libraries on Python 3.5_


Another option was to get the links where PDF files are hosted through 'requests' and then parse them using PyPDF2 and Beautiful Soup. However I did not go for it for the following reasons:

1. PyPDF2 does not work on secured PDFs

2. My code broke several times as some PDFs were taking more time to open up. However, I was able to deal with it by using ```time.sleep(3)```

3. It was taking more memory.
