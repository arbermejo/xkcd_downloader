# xkcd_downloader

Python Script to download all the comics from **xkcd.com** .

## Usage

You just have to run it by typing: **python download_xkcd.py**. It automatically creates an **xkcd** folder and a **last** file. All your downloaded images will be saved in the **xkcd** folder, and the **last** file is where the last downloaded link is stored (**don't delete or modify it unless it's strictly necessary**).

## Tips and tricks

The URLs end with a *__number__* (for instance: 1350) so, if you have any errors during download and the script doesn't skip them automatically, you can manually change the value in **last** to *__number - 1__* (for instance: 1349) and it will skip that file and resume the download from the next one.

## Python requirements

- requests
- BeautifulSoup4

You can install python dependencies using pip install -r requirements.txt

## Enjoy!!! :grinning:
