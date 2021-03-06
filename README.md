# Procyclingstats.com-webscraper

This repo contains data about pro cycling races and cyclists, as well as the python code to retrieve it.

The data is scraped from the procyclingstats.com website. The data contains base informations about riders and urls used to retrieve those informations. 

## Usage

Feel free to download the datasets.

You can also download the python code and adapt it for yourself. Because procyclingstats.com often changes its html layout, you'll potentially have to adapt the beautifulsoup parsing. To avoid getting blocked by the pcs server, the scraper spends a lot of time waiting, making the execution really long. 
 
## Examples of the data
 
### Rider data

| ID | Fullname | Teamname | Birthdate | Country | Height | Weight |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | Adam Yates | Mitchelton-Scott | 19920807 | Great Britain | 1.73 | 58.0 |
| 6 | Adrián González | Burgos-BH | 19920913 | Spain | 1.71 | 63.0 |

### Stage data

| ID | Stage_Name | Date | Stage_Type | Start | Finish | Race_ID | Stage# | Length | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 94 | Tour de France 2015  Stage 9 (TTT) | 2015-07-12 | TTT | Vannes | Plumelec | 17 | 9 | 28.0
| 130 | Vuelta a España 2015  Stage 9 | 2015-08-30 | RR | Torrevieja | Cumbre del Sol. Benitachell | 21 | 9 | 168.3

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## todo-list
- [x] Repair stage data

- [x] Add race/stage data generating code

- [ ] Fetch result data
