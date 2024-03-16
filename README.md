# PredictCAHousingPrices
### Predict California Housing Prices

**Objective:** 
Given the rising cost of California homes, I seek to predict the costs of California houses and learn more about spefici correlations that drive the median house value.

![CAhousing](https://github.com/dkham/dkham/assets/72950291/e7c7cab9-e9c1-479d-b6e9-401c3255266b)

**Method:**
Created a Liner Resression Model and Random Fored with GridSearchSV and accuracy scores to evaluate the perormance.

**Lessons:**
- There is a correlation with the size of the house to higher prices houses, however, median income of homeowners had an even greater correlation higher prices (this was not as expected).
- As one can expect, homes closer to the ocean were also found to have a correlation to higher prices homes.
- Takwaway: keep in mind wealthier neighborhoods as the income of homeowners within a specific block is likely to drive higher prices on California homes.


**Dataset Definitions:**
1. longitude: A measure of how far west a house is; a higher value is farther west
2. latitude: A measure of how far north a house is; a higher value is farther north
3. housingMedianAge: Median age of a house within a block; a lower number is a newer building
4. totalRooms: Total number of rooms within a block
5. totalBedrooms: Total number of bedrooms within a block
6. population: Total number of people residing within a block
7. households: Total number of households, a group of people residing within a home unit, for a block
8. medianIncome: Median income for households within a block of houses (measured in tens of thousands of US Dollars)
9. medianHouseValue: Median house value for households within a block (measured in US Dollars)
10. oceanProximity: Location of the house w.r.t ocean/sea
