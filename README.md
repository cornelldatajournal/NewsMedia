# NewsMedia
Repository for the News Media Group FA '24


How to replicate:

Our work is stored in Colab Python notebook files, with the txt files of our article data stored in another directory. 

To replicate our results for any country's data exactly, clone this repository and open any Python notebook. 
Scroll down to the cell that reads from the txt files, and run every cell that comes after the generate the world cloud unless otherwise specified. 

If you would like to run your own scraping operation, run every cell in any notebook. Make sure to have your own API key for Newzdata.io from here: https://newsdata.io/
It is free at the levels of API calls that we're making on this project.

For China, the process to scrape and translate was a harder and different than the other countries, so it is split into two files, one for scraping and one for translating and making world clouds. 
