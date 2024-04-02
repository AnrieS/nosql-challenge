# nosql-challenge


The purpose of this module challenge is to an analysis for the UK Food Standards Agency and evaluate various establishments across United Kingdom and discover their food hygiene rating. The food magazine editors, “Eat, Safe, Love” is the client for this project, their journalists need help writing for future food articles.

The first part of this challenge is to import the establishment json file from my terminal and create the database and then create the collections establishments. The important libraries that are needed for this challenge are PyMongo and Pretty Print. 

The next part is to update the database and modify changes requested by the magazine editors to include a new establishment called ‘Penang Flavors’ at Greenwich before creating any queries and analysis on the database. After adding in the new establishment, the magazine editor wanted to exclude any establishments in Dover. A filter query included with a removal code was needed to ensure that they were deleted.

The third part of the challenge was to do exploratory analysis on specific questions the editors have requested. However, there are some things that needed to be done for programming before executing any exploratory queries. Some notes that the editors wanted to explore was the “Rating Value” and the location of the establishments of which the food authority rated highly to low rating from 1-5, higher value meant better rating. Non-numeric values such as “Pass” or “AwaitingInspection” was needed to be set as null during the setup before converting ratings and integers.

After the setup of the database, a questions that needed to be answered are: “Which establishments have a hygiene score of 20?”, “Which establishments in London have a RatingValue greater or equal to 4?”, “What are the top 5 establishments with RatingValue of 5, sorted by lowest hygiene score to the nearest restaurant added to Penang Flavors?”, and “How many establishments in each local authority area have a hygiene score of 0?”

The final step of the challenge is creating findings and descriptive analysis on the findings.

Some of the establishments with a hygiene score that equal to 20 are:
•	“The Chase Rest Home” 
•	“Brenalwood”
•	“Melrose Hotel”
•	“Seaford Pizza”

Establishments that have a rating value of 4 or greater are:
•	“Charlies’”
•	“My City Cruises Erasmus”
•	“Benfleet Motor Yacht Club”
•	“Coombs Catering t/a The Lock and Key”

What are the top 5 establishments with a `RatingValue` rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
•	“Wolf House Resid. Home”
•	“Sultan Kebab House”
•	“Magic Work”
•	“Roochi LTD”
•	“Northall CPC”

How many establishments with a hygiene score of 0 by each Local Authority area?
•	“Thanet”
•	“Greenwich”
•	“Maidstone”
•	“Newham”
•	“Swale”
•	“Chelmsford”
