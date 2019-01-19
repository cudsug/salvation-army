# Optimizing Salvation Army Donations in Champaign and Urbana

## Organization Name
Salvation Army
 
## Local Sponsor
Randy Summit, Major

## Overview
The Salvation Army exists to meet human need wherever, whenever, and however we can.  To meet local needs, the Salvation Army will assess the needs of each community in which they serve. They work to understand the obstacles, hardships, and challenges native to the area's particular population.

## Problem Statement
Monetary donations are a key mechanism for funding activities for local chapters of the Salvation Army.  During the holiday season in November and December, bell ringers are located around the area to allow for donations near businesses.  The locations are chosen based on the business being open to the Salvation Army being present for donations.  However, locations that are not in use could be pursued as new donation locations and decisions could be made to more strategically locate the limited volunteers and staff available to be present.  For this community data science challenge, there are two specific areas of focus:

1. Diagnostic: determine the key factors for Salvation Army donations.  This could be analyzed along with weather data or other demographic/geographic data.   
2. Predictive: recommend new locations for the Salvation Army to place bell ringers for donations during the holiday season.  This could be overlaid with other census or home price data to assess where available income could be available for donations.
 
## Evaluation criteria
For each the diagnostic or predictive focus areas, the evaluation will be determined by the use of available data from Salvation Army and other sources to provide evidence for your recommendation or findings.

## Data Details

### cu_salvationarmy_2018.csv

Salvation Army donation data by bell ringing location in the 2018 holiday season.

| Field Name | Description |
| ---------- | ----------- |
| Location | Business name and city |
| Description | Specific location for the business, if multiple donation spots are utilized |
| Address | Mailing address for the business |
| City | City location for the business |
| State | State location for the business |
| Zip_Code | Zip code location for the business |

After the business metadata, there are columns for donation amounts for the location for each day from November 16th through December 24th and a final column for the total donation amount.
