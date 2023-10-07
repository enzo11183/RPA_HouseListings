# RPA_HouseListings
Extracting Property Listings from zillow.com.

This bot scraps real estate listings in a city (given by user) from zillow.com; in these specifications:
-for sale
-home type: house

Retrieved info preprocessed (listing with an empty column will be discarded, full address column will be divided into Street Address, City, ZIP etc.), and sorted in ascending order of bedroom and bathroom number.
Finally, with these information, listings.xlsx created.

After initial creation of listing.xlsx, if the given input does not exists, these new records of  new city will be added to the same xlsx as new sheet. If the given input is same as one of the existing sheets, that sheet will be recreated.


![image](https://user-images.githubusercontent.com/46426033/230650760-e7f813b9-8bf6-41d4-a5b0-9be746f1613c.png)
![image](https://user-images.githubusercontent.com/46426033/230650959-e90bcc45-357a-446c-b47b-20fe15460e0f.png)
![image](https://user-images.githubusercontent.com/46426033/230651182-cafeb6ba-9076-4929-9872-b8f03711e268.png)
![image](https://user-images.githubusercontent.com/46426033/230651251-245aaec1-88fd-48b3-bf5d-7c0a53353e32.png)

Required programs to run this bot:
-Uipath, Excel and Firefox.

For further instructions in Turkish, check PropertyListing.pdf.
