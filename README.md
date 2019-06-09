# CTC16-Air-Champs

AIR CHAMPS

We took on 2 scopes of work for the Weekend;

Idea 1. Dashboard

Opportunity 4. Data Calculations and triggers

Plan;

Work concurrently on these, initially in 'single player mode'

While the team 'Data Gathering' were working on their APIs we focused on pulling sensor data directly from a single sensor in order to rapidly prototype some of the dashboard analytics required;

Last Sensor Reading (gives current reading)
Daily Average (Over 24 hours)
Daily Maximum (In the last 24 hours)
We acheived this for the live sensor data (get_mean)

NEXT STEP (working) convert this python script to direct to the Google Cloud Data store (as developed by Data Gathering team).

Using their API we sucessfully pulled the data as a JSON Object into Python

CURRENT HOLD: Reformatting the JSON file from the API into a Pandas Data Frame (Working)

Dashboard Visulisation: Prototype Completed (refer to screen shots https://github.com/CodeTheCity/CTC16-Air-Champs/tree/master/screenshots)
The https://github.com/CodeTheCity/pollutionpatterns/tree/master/chart  code was updated charts and a new D3 Gauge was added in this repo.

Workflow: WORKING - refer to Workflow PDF

This describes the data flow process
