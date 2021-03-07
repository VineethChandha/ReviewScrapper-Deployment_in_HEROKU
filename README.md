# ReviewScrapper-Deployment_in_HEROKU
# https://reviewscraper-vineeth.herokuapp.com/
## 1)Introduction:
Web scraping is a technique using which the webpages from the internet are fetched and parsed to understand and extract specific information similar to a human being. Web scrapping consists of two parts:

1. Web Crawling: Accessing the webpages over the internet and pulling data from them.
2. HTML Parsing: Parsing the HTML content of the webpages obtained through web crawling and then extracting specific information from it.


* For example, if we open filpkart.com and search for ‘iPhone’, the search result will be as follows:


![image](https://user-images.githubusercontent.com/69765021/109957734-5e970580-7d0b-11eb-8ffc-38db4b908333.png)

* Then if we click on a product link, it will take us to to the following page:


![image](https://user-images.githubusercontent.com/69765021/109957908-9736df00-7d0b-11eb-90f2-78afff74f5ad.png)

* If we scroll down on this page, we’ll get to see the comments posted by the customers:


![image](https://user-images.githubusercontent.com/69765021/109957998-b9306180-7d0b-11eb-8a31-299f91fb50e6.png)

Our end goal is to build a web scraper that collects the reviews of a product from the internet.

Hence, web scrappers are applications/bots, which automatically send requests to websites and then extract the desired information from the website output.

This Project is built to retrieve the Flipkart product reviews according to the search made. This Project is deployed in Heroku and accessed through below link.

https://reviewscraper-vineeth.herokuapp.com/


## 2)Prerequisites:
* Python installed.
* A Python IDE (Integrated Development Environment): like PyCharm, Spyder, or any other IDE of choice.
* Flask Installed. (A simple command: pip install flask)
* [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli).
* Basic understanding of Python and HTML.

## 3)Python Implementation
Note: I have used PyCharm as an IDE for this project.
1.	Let’s create the folders as shown in the repository.
   
* base.html: It acts as the common building block for the other two HTML pages.
*	index.html:  Home page of our application.
*	results.html: Page to show the reviews for the searched keyword.

2. Install all the required libraries using **pip install -r requirements.txt**.
3.	Now, let’s understand the flow:
a. When the application starts, the user sees the page called ‘index.html’.
b. The user enters the search keyword into the search box and presses the submit button.
c. The application now searches for reviews and shows the result on the ‘results.html’ page.

### Please see the [WEB-Scraping_of_Reviews](https://github.com/VineethChandha/WEB-Scraping_of_Reviews) Repository to get more understanding of the code and project.


## 4)Deploying to Heroku.
Please follow the [Heroku_deployment_process](https://github.com/VineethChandha/ReviewScrapper-Deployment_in_HEROKU/blob/main/Heroku_deployment_process.txt) notebook.


**Home Page**(we get this once we click https://reviewscraper-vineeth.herokuapp.com/):

![image](https://user-images.githubusercontent.com/69765021/110237892-8503ad80-7f64-11eb-96d0-c4b98874ada1.png)


**Search Result:**
![image](https://user-images.githubusercontent.com/69765021/110237915-a6649980-7f64-11eb-9690-c1c437b2caf6.png)

# Note:
The class IDs used might change when the flipkart website gets updated **It might be one of the reason for not working of the app**. Please update the ids accordingly.

## Thank you :pray:
## Happy coding :satisfied:
