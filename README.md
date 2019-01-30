# assignments

(1) Assignment - Crijns, Romeijn: https://stefanromeijn.github.io/assignments/CrijnsRomeijn.html

(2) Python attachment: https://github.com/StefanRomeijn/assignments/blob/master/README%20-%20Python%20attachment.py

To run attachment: 
1) Make sure Python is installed;
2) Make a folder and copy the script above in there;
3) In command prompt, run the following commands;
    3.1) pip install docopt
    3.2) pip install requests
    3.3) pip install Beautifulsoup4
    3.4) pip install lxml
3) In command prompt, make sure you are in the right directory (the folder made in step 2). Do so by using the cd command;
4) Run the first part of the script (download 10-K) by calling the following command in command prompt;
    Python EdgarSearch.py download
5) Run the second part of the script (parse MD&A and wordcount) by calling the following in command promt;
    Python EdgarSearch.py mdatool --keywords=future,will,next_month,next_quarter,next_year,next_fiscal,next_period,upcoming_month,coming_month,coming_quarter,coming_year,coming_fiscal,subsequent_month,subsequent_quarter,subsequent_year,subsequent_fiscal,following_month,following_quarter,following_year,following_fiscal
