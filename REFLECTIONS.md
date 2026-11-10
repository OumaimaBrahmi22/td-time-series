Before assuming that historical CO2 data was unavailable, I would have checked the Open-Meteo Air Quality API documentation and tested a request for historical data using the past_days parameter. This would have allowed me to verify the actual availability of historical observations before choosing a synthetic dataset.

Prediction: Rising.
I expect atmospheric CO2 in Le Mans to rise over the selected 90-day period. During summer, vegetation absorbs CO2 through photosynthesis, while this absorption generally decreases in autumn as plant activity slows down.

Stage 6 : extension 
I extended the data collection pipeline to a second location, Sfax, Tunisia. 
I changed the geographic coordinates in the collection script and reran the 
github actions workflow on a separate branch. This demonstrated that the 
pipeline can be reused for another geographical location without changing 
the overall analysis process.
