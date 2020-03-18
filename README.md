# Fortnite-News-Image-Generator

Generates images of the fnbr news tab from the API. direct image available at https://ca-cdn.xyz/api/news.png. Windows and Linux Support.

##  Dependencies

- python 3.3+
- pickle
- PIL
- fortnite_api
- requests

## How to Run

`git clone` This repository and run main.py with python3. On the first time running it should download all the required files and run the script. It should take ~ 7 secconds to fully finish and will output a news.png file. This has been tested on both windows and linux.

After the firt time running it will check every 100 secconds for an update in the API and download the updated news image if it does.
