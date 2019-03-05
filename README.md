### Get information about ordinances with zoning reclassification

##### First get some ordinance info from: https://chicago.councilmatic.org/

Run scrape_chicouncilmatic.ipynb. The output is a json, with one dictionary for each ordinance. The dictionary includes: **ordinance id**, **date**, **year**, **sponsors**, **sponsors' wards**, **address**, **status**.  Only ordinances since 2015 are acquired.

##### Second, get some additional info about the property & ordinance from: https://www.chicagocityscape.com

Run scrape_chicagocityscape.ipynb. The output is a modified json, with a dictionary for each ordinance. Additional information has been added to each dictionary, including: a summary of the ordinance, place information, and key players (e.g. architect, owner, etc)
