# LinkedIn Job Postings Crawler

This repository contains code for crawling LinkedIn job postings. It includes a submodule for the crawling library and client code for performing the crawling job.

## Disclaimer

Please note that the crawling process may not work reliably for collecting more than 30 records due to unexpected halts (Maybe Linkedin detect this program is bot) in Selenium. I am actively working to address this issue and welcome any feedback or contributions from team.

## How to Use

1. Set up your LinkedIn credentials by creating a `credential.json` file with the following format:

   ```json
   {
     "username": "your_linkedIn_username",
     "password": "your_linkedIn_password"
   }
