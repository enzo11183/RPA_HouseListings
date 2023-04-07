# RPA_HouseListings
Extracting Property Listings from zillow.com
This bot scraps real estate listings in a city (given by user) from zillow.com; in these specifications:
-for sale
-home type: house

Retrieved info preprocessed (listing with an empty column will be discarded, full address column will be divided into Street Address, City, ZIP etc.), and sorted in ascending order of bedroom and bathroom number.
Finally, with these information, listings.xml created.
