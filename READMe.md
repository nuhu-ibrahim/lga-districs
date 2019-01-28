# The full Nigerian states, local government areas, senatorial districts and representative districts

## How to use
1. Create a database of your choice
2. Import the file nigeria_lga_districs to the created database

## Information about the tables
i. 	State table: Contains all the states in Nigeria
ii.	Representative district table: Contains all the 360+ representative districts in Nigeria with a foreign key named state_id that links each district to the state it belongs
iii.Senatorial District table: Contains all the 100+ senatorial districts in Nigeria with a foreign key named state_id that links each district to the state it belongs
iv. Local Government Area table: Contains all the 760+ local governments in Nigeria wiht foreign keys state_id, senatorial_districs_id and representative_district_id that links each local government to the state, senatorial districts and representative districts they belong to respectively

## Final note
It took me a long time to compile this list, please leave a comment if it become usefull to you