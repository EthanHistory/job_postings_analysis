# LinkedIn Job Postings Crawler

This repository contains code for crawling LinkedIn job postings. It includes a submodule for the crawling library and client code for performing the crawling job.

## Disclaimer

Please note that the crawling process may not work reliably for collecting due to unexpected halts (Maybe Linkedin detect this program is bot) in Selenium. I am actively working to address this issue and welcome any feedback or contributions from team.

## How to use?
1. clone this repository with recursive option
```
git clone --recursive {project url}
```

2. create conda environment with python version 3.11.7
```
conda create --name {environment_name} python=3.11.7
conda activate {environment_name}
```

3. install necessary packages
```
pip install selenium
pip install -e ./custom_linkedin_scraper
```

4. Set up your LinkedIn credentials by creating a `credential.json` file with the following format:

   ```json
   {
     "username": "{your_linkedIn_username}",
     "password": "{your_linkedIn_password}"
   }

5. Run the notebook "linkedin_job.ipynb"