# Performance_Assessment-MPC
The code can be used to perform assessment on air quality of Million Plus cities (MPC) in India. The code has been developed basically taking into account the criteria and steps put forth by the Central Pollution Control Board (CPCB) for evaluation

# This code is developed using R Language

# Essential steps to be taken into account while using the R-Markdown
1. Make sure a seperate folder is created with all the air quality data downlaoded from the CPCB website
2. Set the working directory according (Chunk 1: Initate the Working Directory)
3. Make sure you have all the columns namely Date, PM2.5, PM10 or else add the missing columns manually (Chunk 3: Check for 3 mandatory columns [Date, PM10, PM2.5])
4. Choose the desired pollutant either PM10 or PM2.5 (Chunk 7:Choose the columns containing the desired pollutant)
5. Assign the Finanical year (Chunk 12: Total number of days for each Finanical Year (FY))
6. Assign the Finanical year (Chunk 19: Assign the Finanical Year (FY))


# Deliverable
1. Chunk 21 computes the mean value of the desired pollutant for each FY
2. Chunk 22 computes the AQI for each FY (Note the chunk is advaisable only if the pollutant is PM10)
