# Product Image Parsing Challenge

This is a quick challenge on parsing product images out of a website. For this challenge we will be using the Urban Outfitters site. The challenge is writing a function that, given a category page identifier, finds all the product images for that category.

For example 'MENS_SHOES' could be one category identifier and that would yield to a URL http://www.urbanoutfitters.com/urban/catalog/category.jsp?id=MENS_SHOES. The function should just take this category identifier, create the appropriate url to get the product listings, get HTML from the URL, parse the HTML and return a list of all product images for that category.

Please code this in python and use the libraries highlighed in the requirements section.

## Requirements:

* Python
* [Pip](https://pypi.python.org/pypi/pip) (to install the libraries in requirements.txt)
* [requests](http://docs.python-requests.org/en/latest/)
* [beautifulsoup4](http://www.crummy.com/software/BeautifulSoup/)

## Deliverable:

* Once the challenge is complete, i.e. you write a python module with the function, please submit a [pull request](https://help.github.com/articles/using-pull-requests) to this repo.
