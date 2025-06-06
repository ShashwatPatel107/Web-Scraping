# Web Scraping Dynamic Website Using Selenium

## Goal

To create helping function to built dataset of video informations on perticular topic.

---
## Overview
Scraping YouTube videos on Python Language using Requests, Pandas, Selenium based on word(s) provided by user.

Scraping Video Informations like Title, Channel Name, video Link etc.

Get result for number of videos.

Store Data in .CSV file.

---


## Outline
Understanding the structure of the YouTube Website.
Installing and Importing required libraries.
Getting the keyword(s) from user.
Using we search videos for the Keyword.
Download the webpage URL using selenium Web-driver
Parsing the Top Videos get the below attributes using functions.
A. Video Title
B. Name of the Channel C. No. Of views
D. Video Length E. Thumbnail image
F. Video Link 6. Create helper functions to get combined lists 7. Storing the extracted data into a dictionary. 8. Compiling all the data into a DataFrame using Pandas and saving the data into .CSV file.

---

## Features

* Automates dynamic content scraping via browser simulation
* Supports user interaction (e.g., clicking buttons, dropdowns)
* Data output to CSV or JSON formats
* Custom wait strategies for reliable scraping
* Tested on ChromeDriver and Firefox (geckodriver)

---

## Future Work

* Add multi-page crawling and error handling
* Integrate proxy rotation and headless mode
* Export data to databases (PostgreSQL, MongoDB)
* Deploy on a schedule using cron or Airflow

---

## License

Licensed under the [MIT License](LICENSE). You are free to use, adapt, and share with attribution.

---
