# My Roadtrip Diary

This repo is forked from my old school account and was my New Maps Plus project. Some link rot needs to be fixed to restore map slider and info bar. 

This map is a spatial diary of roads I have travelled on through the course of my life. It is intended to serve as a spatial auto-biography.

The map was made using leaflet. For data collection I created a [spreadsheet](https://github.com/DevinLeeBartley/roadtripData/blob/master/trips.csv) of all the road trips I have taken and fed them into [this](https://github.com/DevinLeeBartley/roadtripData) Node.js script which sent the value to the Google Directions API and returned encoded polylines, which were decoded and convered into GeoJSON features.
