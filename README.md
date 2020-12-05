# council-tax-band-scraper
A program that will download all council tax band information for a specified local authority in England.

To use the program, go to terminal and move to the top directory. From there, execute the line

scrapy crawl england -a local_authority="Lewisham" -o  "Data/Lewisham.csv"

This will scrape all council tax band information for the Local Authority "Lewisham" and store it in a csv file in the Data folder. Lewisham can of course be replaced with any other Local Authority in England (so no Isle of Man or Channel Islands). 
