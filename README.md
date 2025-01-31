# Geospatial 

Credit: Realtime Trains

## Set project environment
- use conda to create an isolated envrionment 
- dependencies: fastapi, uvicorn, requests, python-dotenv, pandas, matplotlib, folium, geopandas
- initialise github repository for version control
- store environment variables to connect to Realtime Trains API securely 
- test connection to API

## Build the REST API 
### Set up a FastAPI project
-  initialise a FASTAPI project to structure the API

### Create basic endpoints:
- /api/trains: Get train  services btw stations. param: origin, destination
- /api/delays: Get data about delayed trains. Param: o, d 

![alt text](images/image-11.png)


## Analyse spatial data 
- analyse delay clusters `test_df.py` 
Total delays in the past 6 days between Finsbury Park to Kings Cross found: 1267
- chart with Matplotlib

![alt text](image.png)

## Create Database 
## Optimazation with partition and indexing 


[In Progress]
- identify congestion hotspots (routes or stations)
- map with Folium 

## Data Visualisation
- plot stations and train routes 
- delay heatmaps 
- operator performance dashborad
- time-based delay trends

## Optional
### CI/CD with Docker
### GitHub Actions
