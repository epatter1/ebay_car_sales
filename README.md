# German Used Cars on Ebay

[View Here!](https://nbviewer.jupyter.org/github/epatter1/ebay_car_sales/blob/master/Exploring%20Ebay%20Car%20Sales%20Data.ipynb) :eyes:

Here I work with a dataset of used cars from eBay Kleinanzeigen, a [classifieds](https://en.wikipedia.org/wiki/Classified_advertising) section of the German eBay website. 
 > ### Goal: To clean the data and analyze the included used car listings.

The dataset was originally scraped and uploaded to Kaggle. A few modifications have been made from the original dataset that was uploaded to [Kaggle](https://www.kaggle.com/orgesleka/used-cars-database/data):

50,000 data points were sampled from the full dataset to ensure code ran quicker. 
I chose a "dirtier" dataset a bit to more closely resemble what you would expect from a scraped dataset (the version uploaded to Kaggle was cleaned to be easier to work with)
The data dictionary provided with data is as follows:

* *dateCrawled* - When this ad was first crawled. All field-values are taken from this date.
* *name* - Name of the car.
* *seller* - Whether the seller is private or a dealer.
* *offerType* - The type of listing
* *price* - The price on the ad to sell the car.
* *abtest* - Whether the listing is included in an A/B test.
* *vehicleType* - The vehicle Type.
* *yearOfRegistration* - The year in which the car was first registered.
* *gearbox* - The transmission type.
* *powerPS* - The power of the car in PS.
* *model* - The car model name.
* *kilometer* - How many kilometers the car has driven.
* *monthOfRegistration* - The month in which the car was first registered.
* *fuelType* - What type of fuel the car uses.
* *brand* - The brand of the car.
* *notRepairedDamage* - If the car has a damage which is not yet repaired.
* *dateCreated* - The date on which the eBay listing was created.
* *nrOfPictures* - The number of pictures in the ad.
* *postalCode* - The postal code for the location of the vehicle.
* *lastSeenOnline* - When the crawler saw this ad last online.

