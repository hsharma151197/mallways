# mallsites-selenium-scraper

## Dev Setup
- Java 1.8
- Gradle 4.2
- Scala 2.11.7
- Install ChromeDriver `brew tap homebrew/cask && brew cask install chromedriver`
- Python3
- Node v8 (Recommended way is to install Node via NVM) 
- Install git-lfs and track image files

### Python Scripts Setup
- pip3 install requests
- pip3 install csv

### Firebase Setup to deploy images
- Install firebase-tools `npm install -g firebase-tools`
- firebase init 
- firebase deploy --only hosting

### Install git lfs
- brew install git-lfs
- git lfs track data/firebase_host_root/images

## Scraping 

### Phoenix MarketCity, Bengaluru
- Categories on the mall's website are not separable by URL so we select the categories checkbox and save it as file
- Next we comment jquery code in the html page because otherwise their script was running and chaning the layout with all shops
