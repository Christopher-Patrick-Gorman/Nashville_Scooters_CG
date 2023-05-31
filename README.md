## Metro Scooters Analysis
In May of 2018, Bird dropped hundreds of scooters on the streets of Nashville with no permission. In response, Metro sued, which caused Bird to remove and wait for permits. Metro began developing regulations for scooters and other shared urban mobility devices (SUMDs). In 2019, the Metro Council passed legislation enacting a one-year pilot program for scooters. For this project, you have been provided with the data for 3 months of this pilot program with the goal of reporting on usage trends and generating recommendations for quantity and distribution of scooters in Nashville.

Metro would like to know what the ideal density of available scooters is, which balances the objectives of
enabling scooters to serve transportation goals,
discouraging scooters from piling up on sidewalks,
keeping it economically viable for companies to operate equitably in the city.

This data for this project can be downloaded as a Postgres backup from https://drive.google.com/file/d/1BXAfByFvHCwX0G1BvTCQ373qKm7wE4Y-/view?usp=share_link.

Some notes about the data:
When not in use, each scooter will report its location every five minutes. This data is contained in the scooters table.
Both tables contain a large number of records, so think carefully about what data you need to pull in a given query.

Start with addressing these questions:
SUMDs can provide alternative transportation and provide "last mile" access to public transit. How often are trips starting near public transit hubs? You can download a dataset of bus stop locations from https://data.nashville.gov/Transportation/Regional-Transportation-Authority-Bus-Stops/p886-fnbd.

Deliverables:
At the conclusion of this project, your group should deliver a presentation which addresses the following points:
* Does it appear that scooters are used as "last mile" transportation from public transit hubs to work or school?
