### Get information about ordinances with zoning reclassification

##### First get some ordinance info from: https://chicago.councilmatic.org/

Run scrape_chicouncilmatic.ipynb. The output is a json, with one dictionary for each ordinance. The dictionary includes: **ordinance id**, **date**, **year**, **sponsors**, **sponsors' wards**, **address**, **status**.  Only ordinances since 2015 are acquired.
