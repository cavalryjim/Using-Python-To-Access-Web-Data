# Using Python To Access Web Data
All folders of this repository contain a mini project taken from the online course 
 [Using Python to Access Web Data](https://www.coursera.org/learn/python-network-data). 

* **Exploring the HyperText Transport Protocol using socket**

The code retrieves a document using the HTTP protocol using `socket` so as to examine the HTTP Response headers as well as text.

* **Extracting Data From JSON**

The code reads the JSON data from a URL using `urllib.request` and then parses and extracts the comment counts from the JSON data using `json` module, and prints the computed sum of the numbers in the file.

* **Extracting Data From XML**

The code reads the XML data from a URL using `urllib.request` and then parses and extracts the comment counts from the XML data using `xml.etree.ElementTree as ET`, and finally computes the sum of the numbers in the file.

* **Extracting Data With Regular Expressions**

The code reads through and parses a file with text and numbers using `regex` extracting all the numbers in the file and then computing the sum of the numbers.

 * **Following Links In HTML Using Beautiful Soup**
 
The code uses `urllib.request` to read from the HTML, parses the data using `BeautifulSoup`, extracts the `href` = values from the anchor tags, scans for a tag that is in a particular position relative to the first name in the list, follows that link and repeats the process 7 times and reports the last name it finds.

* **Scraping Numbers from HTML using BeautifulSoup**

The program uses `urllib.request` to read the HTML and `BeautifulSoup` to parse the data, extracting numbers and compute the sum of the numbers in the HTML file.

* **Using the Geo JSON API to get ```place_id``` for a location**

The code contacts Geo JSON API to retrieve information about a specific location in JSON format and parses that data, and retrieves the first `place_id` from the JSON. A place ID is a textual identifier that uniquely identifies a place as within Google Maps.
 
 My blog on this topic can be found [here](http://www.aashitak.com/data%20science/Scraping-data)
