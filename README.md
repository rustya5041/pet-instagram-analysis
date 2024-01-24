# pet-instagram-analysis


This repo contains the script(s) for some useful instagram json data analysis for f&amp;f :) 

Current scripts: 
- `instagram_follow_analysis`

`instagram_follow_analysis` processes the data from the Instagram followers and following JSON files and creates dataframes to check the ppl that you follow but they don't follow you back and vice versa.

--- 

### Instructions for `instagram_follow_analysis`
First, you need to download your instagram data. No need for any of external tools - Instagram allows to do that by default (*works ok in 2024*).

Option 1:
- Follow the link: https://www.instagram.com/download/request

Option 2 (if you are not a fan of clicking on random sketchy links posted on github):
- Log to Instagram via your web browser
- Go to your profile
- On the left bottom side click `'еще / more'`
- Select `'ваши действия / your actions'`
- Select `'скачать данные / download data'` at the bottom of the page
- Click `'запросить файл / request file'`
- Click `'выбрать типы информации / select information types'`
- Among `Контакты / Contacts` check the `"подписки и подписчики / following and followers"` box
- Select the appropriate `диапазон дат / date range`
- In the `формат / format` field select `JSON`
- Hit the `запросить файл / request file` button
- Wait a few minutes - typically 3-10 minutes depending on the amount of requested data
- Refresh the page and click `'скачать файл / download file'`
- Unzip the file and copy the path to the `followers_and_following` folder

Once you've downloaded the data, download and run `instagram_follow_analysis.ipynb` notebook :)

