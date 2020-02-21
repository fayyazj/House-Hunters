# House-Hunters
 
In this project, my team wrote a module that scraped Zillow for house listings in a provided area (for this project, we used Atlanta). The module also returned the details of those homes (Zillow ID, Zestimate, Lot Size, Square Feet, Bedrooms, Bathrooms, Year Built, Home Type, Listing Link). We then wrote this data into an excel file and read the file into a pandas dataframe for data munging.

Our objective of this project was to create a program that takes into account user preferences when they search for their dream home, and to apply weight to the areas the user identified as being more important in order to filter/rank the final list of home options. The user is first asked what their ideal home price, lot size, square footage, # of beds/baths, year built, and home type is. Then, the user is asked to indicate how important each criteria is to them by assigning a value between 1 and 5. Our program will then filter through for houses that fit those criteria and return a list of homes ranked by order of what the most ideal pick should be.

In order to view our notebook, please visit this link: https://nbviewer.jupyter.org/github/fayyazj/House-Hunters/blob/master/House_Hunters_Excel.ipynb
