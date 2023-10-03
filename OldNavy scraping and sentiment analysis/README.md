# The Python file in this directory is to get the product and review information of Old Navy's Men's Jeans Category. 

***

Download the directory and open the iPython notebook in Jupyter Notebook.

Install selenium and webdriver_manager with the following commands if not already done

```
!pip install selenium

!pip3 install webdriver_manager
```

Import beautiful soup to scrape content from the pages based on the HTML elements on each page.

Execute the code as given in the Python notebook and copy the output into a CSV file.

After saving it in a CSV file, you will find the below columns:

```
Id - ID of the product
Name - Name of the Product
Color - Color of the Product
Price - Price of the Product
Ratings - Rating for the product
Review_head - Review one-liner
Review - Review of the product
```

### After getting this CSV, sentiment analysis has been performed on the CSV we got which results in the below information.

```
Review - Reviews of a product
Sentiment - Positive/Neutral/Negative
```
