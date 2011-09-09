US Zip Code Data
================

The data provided is based on the data provided by the Zip Code Database Projecthosted on Sourceforge: http://zips.sourceforge.net/

That data itself is based on the 2000 U.S. Census. The file was released as a ZCTA (Zip Code Tabulation Areas) on the Gazetteer website: http://www.census.gov/geo/www/gazetteer/

Why?
----

I needed a database of US zip codes and their cities, states, etc. and discovered the Zip Code Database Project. FasterCSV and LibreOffice refused to parse the CSV provided by the project. Zip codes in the provided data with less than 5 digits were also not prefixed with zeroes. After about 5 minutes of tweaking with Google Refine, all of that was fixed. The CSV file is also about 1 MB smaller.

Updates?
--------

The current data is based off of the 2000 U.S. Census, which means that the data provided is over ten years old. My goal is to update this as soon as the relevant data for the 2010 U.S. Census is released.

License?
--------

Like the Zip Code Database Project, the data provided is in the public domain. Do what you want with it.
