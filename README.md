# Crowdfunding-ETL

Module 8 the ETL process
Data for the Challenge portion can be found in the Module8_Challenge folder.

## Overview
This module was about bringing together a few different skills we have learned so far as we discussed the ETL (Extract, Transform, Load) pipeline.  The end goal was to provide a list of emails that should be notified about the status of the crowdfunding campaign they are associated with.  The challenge presented to us was read in a csv file containing data that was not immediately useful, but needed to be parsed to pull out our data.  I decided to complete this step using regular expressions (regex) and then prepared to transform other parts of the data as necessary.  These included fixing a columns data type and splitting a column so we would have first and last name separately.  The last portion of the ETL process required that we export our cleaner data to a csv and then load it into a SQL database.  Finally after completing the ETL process we ran a handful of queries in order to create our lists of the contacts of each crowdfunding "Live" campaign and each backer associated with these campaigns, which could then be used to contact those indiviuals and update them on the status of the campaign.
