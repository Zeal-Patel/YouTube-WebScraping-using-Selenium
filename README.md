# YouTube-WebScraping-using-Selenium
Scraping Topic Wise Video Details on [YouTube](https://www.youtube.com/) using Selenium


## Introduction

### What is Web-Scraping
Web scraping is the process of extracting and parsing data from websites in an automated fashion using a computer program. It's a useful technique for creating datasets for research and learning.

### Little About YouTube.

YouTube is a free video-sharing website that makes it easy to watch online videos. visitors watching around 6 billion hours of video every month. One reason YouTube is so popular is the sheer number of videos you can find. On average, 100 hours of video are uploaded to YouTube every minute, so there's always something new to watch!

### Project Do Following:
1.   Scraping [YouTube](https://www.youtube.com/) videos on Python Language using Requests, Pandas, Selenium based on word(s) provided by user.

2.   Scraping Video Informations like Title, Channel Name, video Link etc.

1.   Get result for number of videos.
2.   Store Data in .CSV file.

### Objective
To create helping function to built dataset of video informations on perticular topic.

### Outline:
1. Understanding the structure of the YouTube Website. 
2. Installing and Importing required libraries. 
3. Getting the keyword(s) from user. 
4. Using we search videos for the Keyword.
5. Download the webpage URL using selenium Web-driver
5. Parsing the Top Videos get the below attributes using functions.
 
  A. Video Title  
  B. Name of the Channel 	
  C. No.  Of views  
  D. Video Length	
  E. Thumbnail image  
  F. Video Link 
6. Create helper functions to get combined lists
7. Storing the extracted data into a dictionary.
8. Compiling all the data into a DataFrame using Pandas and saving the data into .CSV file. 


CSV file will look something like this!
