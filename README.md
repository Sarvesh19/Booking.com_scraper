# Booking.com_scraper
A python script that scrapes booking.com website for hotels around the world with hotel name,hotel address 
and the amenities provided by them.

Code is in form of jupyter notebook
It uses selenium library of python to automate the task.
Selenium is used because the website,booking.com is dynamic that is it uses javascript so simply beautifulsoup(a python library for scraping)
can't be used in place.

The script finds the tag corresponds to hotel name,address and their amenities and writes the data in .csv file.
