# Boston Airbnb Travel Guide

This script analyzes trends in the Airbnb price and listing data for Boston, Massachusetts, USA. It provides travels going on a trip to Boston to better understand which times of the year are busiest, which neighborhoods suit their travel needs and whether the overall experience in multi-listing homes is different from single-listing homes.

## Table of Contents
* [Installation](#Installation)
* [Project Motivation](#motivation)
* [File Description](#description)
* [Results](#Results)
* [Licensing, Authors, Acknowledgements](#licensing)

## Installation
The code requires Python versions of 3.* and general libraries available through the Anaconda package.

## Project Motivation <a name="motivation"></a>
As a dedicated city traveler myself, I often come across the same questions when I'm looking for accomodation in a city I haven'T been to before. I wanted to leverage the overall Airbnb data of a city, in this case Boston, to try to derive some general guidelines for visiting the city. The questions I looked at were:

* Question 1: What times of the year are especially expensive?
* Question 2: Which neighborhoods should you visit if you're looking for a quieter or more vibrant experience?
    * Question 2.1: What if I want to be very central, which neighborhoods should I choose?
* Question 3: Which neighborhoods are good for a lower-budget vacation?
* Question 4: Is the rating different for listings where the host rents more than one room?
    * Question 4.1: Is there an overrepresentation of certain neighborhoods for single- and multi-listing properties?

## File Description <a name="description"></a>
There is one Jupyter notebook containing the code to answer the above questions. Markdown cells were used to help understand the different steps taken and the conclusions that can be drawn for each question. There are also 5 csv files included.

## Results
The main findings of the analysis have been published in a blog post [here](https://medium.com/@julia.nikulski/here-is-what-you-need-to-know-about-staying-in-boston-with-airbnb-57e81f5296ae).

## Licensing, Authors, Acknowledgements <a name="licensing"></a>
The data used for the analysis comes from [Inside Airbnb](http://insideairbnb.com/about.html) and parts of it have been supplied by kaggle [here](https://www.kaggle.com/airbnb/boston#reviews.csv). There is also licensing information [here](http://insideairbnb.com/about.html) and [here](https://www.kaggle.com/airbnb/boston#reviews.csv). Feel free to use the code as you please and use it for another Airbnb city dataset.
