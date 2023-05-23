# com.Inka.CrawlWebpage
python code for crawl webpage where movie is available, check whether it is playable and store the links in array or csv file
# Prerequisites
A Windows 10/11 PC

Python: Install Python on your system. You can download the latest version from the official Python website (https://www.python.org) and follow the installation instructions specific to your operating system.

Python packages: Install the necessary Python packages using pip, the package installer for Python. You'll need the following packages:

                1. BeautifulSoup: Used for parsing HTML and extracting information from web pages.
               
                2. requests: Used for making HTTP requests to fetch web pages.
                
                3. pandas (optional): Used for storing the links in a CSV file (if you prefer CSV over an array).
                
You can install these packages by running the following commands in your terminal or command prompt:

                1.  pip install beautifulsoup4
                
                2.  pip install requests
                
                3.  pip install pandas
 
# How to launch the project and test:
Step 1: Create a new Python script file and open it in a code editor.

Step 2: Import the necessary modules.
 
         from bs4 import BeautifulSoup
         
         import requests
         
         import csv
         
Step 3: Write the code to crawl the webpage, check movie availability,check it is playable or not and store the links.

Step 4: Save the Python file with a .py extension.

Step 5: Open your terminal or command prompt and navigate to the directory where the Python file is located.

Step 6: Execute the Python script by running the following command:

        python your_script_name.py
        
# Sample output for movie bhoola
Assuming the links are stored in the 'link_array' variable

movie_name = "Bhoola"

print(f"Links for movie '{movie_name}':")

for link in link_array:

    print(link)
    
 Output:
 
 Links for movie 'Bhoola':
 /html/body/script[31]
 https://example.com/movie2
 https://example.com/movie3
                
