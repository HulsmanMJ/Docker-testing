# Docker-testing

With this repo I want to do the following:
1. When a change is made in this repo, a signal will be send to Jenkins (webhook).
2. Jenkins will pull this repo
3. Jenkins will start the scripts and the following will be done:
   a. Download goss and dgoss
   b. Test the new version with goss
   c. Build the new version/software
   d. Deploy the new build 
