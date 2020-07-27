# Tutorial 5 - Python Data Stack 2
Welcome to the fifth tutorial in this series. In this tutorial we are going to round out the Python scientific stack with Pandas! Not the cute and cuddly kind but the data focused kind!

Pandas is the final piece in the Python scientific stack that we have yet to cover. Pandas provides a new data structure in Python as well as some tooling for slicing and dicing your data. It is the equivalent of R's dataframe and some of dplyr's data manipulation. There are few projects where you'll go without Pandas. Pandas provides a great deal of flexibility and comfort not afforded by Numpy alone. Pandas is built on top of Numpy so you aren't losing out on any of those wonderfully optimized vector operations.

Before starting this tutorial you'll need to install pandas and bs4. bs4 is a library that will install some tools for web scraping (i.e. BeautifulSoup), we will be using this to pull in a dataset from an online GitHub repository.

## Resources
- The Pandas documentation and more can be found here: https://pandas.pydata.org/
- Cheatsheets for these sorts of libraries are always super useful
  - Datacamp as usual has a pretty nice one: http://datacamp-community-prod.s3.amazonaws.com/dbed353d-2757-4617-8206-8767ab379ab3
  - Pandas does have an official one though: https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf
- Data types available in Pandas: https://pbpython.com/pandas_dtypes.html
- A more in depth look at Pandas data structures: https://pandas.pydata.org/pandas-docs/stable/getting_started/dsintro.html
- Data formats that Pandas can natively read: https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html