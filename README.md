### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

You need to install Python from source, with an installer from python.org,you will also need the standard data science libraries found in it.Additionally, you’ll need to make sure you have pip available.You can check this by running 'python3 -m pip --version'.

If this doesnt work you can get more directive [from](https://packaging.python.org/en/latest/tutorials/installing-packages/).  


## Project Motivation<a name="motivation"></a>

For this project, I was interestested in analyzing data from AirBnB homes located in Seattle and Boston.  Specifically, I looked at the following questions:

1. How much Airbnb homes are earning in certain time frames and areas)? How does this compare from Boston to Seattle?
2. How much do Airbnb owners charge to rent their home? How does this compare from Boston to Seattle?
3. Is their anything standing out in the listing that helps predict pric? How does this compare from Boston to Seattle?


## File Descriptions <a name="files"></a>

The following are the files available in this repository:

* `AirBnB_Project_1_Analysis.ipynb` - a notebook of the analysis performed following the CRISP-DM process

* `calendar.csv` and `calendar_boston.csv` - csvs containing **home_id**, **date**, **availability**, and **price** for each home

* `listings.csv` and `listings_boston.csv` - csvs containing the **home_id**, **date** of listing, **listing_url**, **listing_name**, **host_name, **response_rate** and many more.
* `reviews.csv` and `reviews_boston.csv` - csvs containing the **home_id**, **date** of review, **reviewer_id**, **reviewer_name**, and reviewer **comments** for the reviewed stays.

It is worth noting here that the reviews and calendar files did not have overlapping dates, and there were no numeric values associated with reviews.

## Results<a name="results"></a>

The main findings of the code can be found at the [blog post available here](https://medium.com/@josh_2774/a-comparison-of-airbnb-homes-seattle-vs-boston-cdc0df2cfcd7).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to AirBnB and Kaggle for the data.  You can find the Licensing for the data and other descriptive information for the [Boston data on Kaggle](https://www.kaggle.com/airbnb/boston) and for the [Seattle data](https://www.kaggle.com/airbnb/seattle).  
