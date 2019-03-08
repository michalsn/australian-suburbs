# Australian Suburbs

All data was gathered from openly available sources - mainly 2016 Census.


### Structure

* data
	* MySQL table with suburbs - there is a lots of additional data though
	* CSV file with the same data as above
* GeoJSON
	* Geometric data for suburbs
	* Geometric data for postcodes

### MySQL/CSV sample data

| ssc_code | suburb      | urban_area    | postcode | state | state_name      | type           | local_goverment_area | statistic_area | elevation | population | median_income | sqkm   | lat       | lng       | timezone         |
|----------|-------------|---------------|----------|-------|-----------------|----------------|----------------------|----------------|-----------|------------|---------------|--------|-----------|-----------|------------------|
| 11344    | East Albury | Albury - East | 2640     | NSW   | New South Wales | Urban locality | Albury (City)        | Rest of NSW    | 246       | 6098       | 38064         | 12.329 | -36.09041 | 146.93912 | Australia/Sydney |
| 12287    | Lavington   | Albury - West | 2641     | NSW   | New South Wales | Urban locality | Albury (City)        | Rest of NSW    | 207       | 12472      | 28080         | 14.778 | -36.02909 | 146.93586 | Australia/Sydney |
| 11678    | Glenroy     | Albury - West | 2640     | NSW   | New South Wales | Urban locality | Albury (City)        | Rest of NSW    | 256       | 3289       | 34944         | 8.058  | -36.05258 | 146.89876 | Australia/Sydney |
| 10027    | Albury      | Albury - West | 2640     | NSW   | New South Wales | Urban locality | Albury (City)        | Rest of NSW    | 166       | 4804       | 40872         | 5.683  | -36.07352 | 146.91573 | Australia/Sydney |
