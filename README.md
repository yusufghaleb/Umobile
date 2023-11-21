# Umobile
New feature for Telecommunications Service Provider Project (SQL)
## System Request
Customers over the last 10 years have indicated that the process of editing their phone/data lines, including adding and activating a new one on their existing plans can be cumbersome; especially since the latter requires a mandatory in-person visit to one of our customer service branches. Although management understood the validity of this, the technology available at the time would not allow for this to be feasible in a way that would not require a wider systems overhaul that would prove very costly, especially given that this process requires complex transactions such as ID validation and the installation of a physical SIM card on the new device.

In the last couple of years, the process has evolved. Smartphone manufacturing companies have begun to incorporate newer technology on their hand-held devices that eliminate the need for a physical SIM card, replacing it with what is known as an embedded SIM, or eSIM, for short. The trend is for this new technology to become the standard, and major firms such as Apple and Samsung already include it in their products. 

We now need this process to be deployed as new modules within our website and mobile apps, so that any phone that currently supports SIM (83% of the devices that work within our network currently do) for any customer with an open account with us, will be eligible to carry out these tasks without having to appear in person at one of our branches.

## Company Information & Business Problem
* **Oragization Name:** U-Mobile
* **Industry:** Telecommunications (Phone Service Provider)
* **Business Problem:** Currently with phone services, customers aren’t able to add a line without rigorous in-person identification verification. U-mobile allows for online identification verification of existing plans. Now existing members can add members to their plan online if they have an e-sim. We chose this organization to allow ease for customers to add lines to existing phone plans without having to undergo long wait times and a service break. 

## Project Details
For the implementation of our new remote line-adding feature into our company’s system, we created a database for the ingestion of customer data. Firstly we defined our entities and their respective attributes within the database, through the creation of the entity-attribute chart. This allowed us to accurately depict the necessary data infrastructure for incoming customer data. Furthermore, we provided descriptions for the entities and attributes. Lastly, we developed our business rules which we used to derive the relationships between the entities within the database. 

Moving to our data models, we created both an entity relation diagram and a third normal form relational model to accurately represent the entities and attributes within the schema. Normalization is a tool to validate and improve a logical design so that it satisfies certain constraints that avoid unnecessary data anomalies. These anomalies include insertion, deletion, and modification anomalies. 

Next, we created our database in MySql using SQL data definition language. We wrote SQL statements to create our schema and then populated it with our entity tables. We made sure we incorporated the correct data types to allow for proper data insertion, ensuring integrity and consistency. We populated the tables with sample customer data and queried the database to ensure proper functionality. 

Our newly created database will catalyze the enhancement of customer user experience within our telecommunications company, allowing customers to conveniently add additional lines to their existing accounts from the comfort of their homes. 

**For the full project details, please check out the project summary pdf file above.**
