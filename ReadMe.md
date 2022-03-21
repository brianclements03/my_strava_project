# MY GPS ACTIVITIES PROJECT

### This readme and github contain information on my Strava and Nike Run Club gps-tracked activities; mostly, this repo is relatively  minor data prep and minimal exploration to prepare data for a thorough Tableau project.

## Project Description
- Are you an avid runner or cyclist? Or both? Ever wondered what the accumulation of all your activities looks like when analyzed or mapped together? 
- This project aims to do an analysis of all the activities that I recorded using the Strava and Nike Run Club (NRC) apps over the past seven or so years.  
## The Plan
- Download and learn about the gpx files that were created for every activity
- Explore the data; compare and contrast the NRC and Strava data
- Parse the gpx files; calculate certain measures I will need
- Merge the files from the two different sources into a single dataframe and .csv
- Export to Tableau and conduct further exploration and visualizations 
## Project Goals
- Find trends in my activities over time
- Visualize all the places I've recorded activities
- Understand gpx data files and rendering them using Python and Tableau
- Have fun learning about an area of Data Science that I've been interested in for a long, long time
## Data Dictionary

## Missing Values

## Initial Questions?
- Are there any unusual speeds or location information? Anomalies
- What's my average distance? Speed? Time? Rides versus runs?
- The usual time of day I record activities
- Gains? Losses?
- What was my fastest ever mile? Longest ever run? Ride?
## Steps to Reproduce
- Download your Strava info from their website
- Download NRC data using the tool listed below at nexporter.bullrox.net
- Install gpxpy and geopy for data manipulation tasks on the gpx files
- Save all gpx files to a folder named 'all_gpx_files' and run the Join_Strava_and_NRC_gpx notebook
- Connect to the resulting csv with Tableau and explore from there
## Key findings/recommendations/takeaways

## Next Steps

## Tools used
- gpxpy: a gpx parser library
- geopy: library for working with geospatial data
- https://nexporter.bullrox.net/ (a website that helps download Nike Run Club gpx files)
## Other notes
- NRC is in miles and minutes; Strava in km and seconds. However, GPX files report meters and seconds