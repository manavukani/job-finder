# Job Finder

This is an online job scraping and analysis tool that provides the user with the ability to filter jobs based on the user’s interest. This allows job seekers to post their CVs and employers to post jobs, hence a perfect site to scrap the job details from.

So, leave the tedious and monotonous task of looking up the job postings to our web app that not only provides the jobs posted every day but helps to filter out the results based on your liking.

# Installation

Check [INSTALL.md](INSTALL.md) for installation instructions for Python, VS Code and MongoDB

# To get started with project
* Clone the repo
   ```
   git clone https://github.com/manavukani/job-finder.git
  
  ```
* Setup virtual environment
  ```
  pip install virtualenv
  cd job-finder
  virtualenv venv
  .\venv\Scripts\activate.bat
  ```
* Install required libraries by 
  
  ```
    pip install -r requirements.txt
  
  ```

* Setup and Connect mongoDB database and Run scraper.py to fetch job details
  ```
    python scraper.py
  
  ```

* After running command 'flask run --debug', in src directory you are good to go
  
  ```
    flask run --debug

  ```


# Tech Stack used for the development of this project
 
* Python
* Flask
* MongoDB
* HTML/CSS
* Selenium
* Beautiful Soup
* Pytest