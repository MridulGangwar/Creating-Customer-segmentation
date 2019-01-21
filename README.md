# Creating-Customer-segmentation

The original dataset contains 1000 entries with 20 categorial/symbolic attributes prepared by Prof. Hofmann.

Several columns are simply ignored, because in my opinion either they are not important or their descriptions are obscure. 
The selected attributes are:

Age (numeric)
Sex (text: male, female)
Job (numeric: 0 - unskilled and non-resident, 1 - unskilled and resident, 2 - skilled, 3 - highly skilled)
Housing (text: own, rent, or free)
Saving accounts (text - little, moderate, quite rich, rich)
Checking account (numeric, in DM - Deutsch Mark)
Credit amount (numeric, in DM)
Duration (numeric, in month)
Purpose (text: car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, vacation/others)

I'm using unsupervised (kmeans clustering and clustering with affinity propagation) to create customer segments.
