## Major Steps:
1. Read in PA_cities_counties and snowstorm_PA as csv
2. Read in PaMunicipalities2022_01 and tl_2021_us_county as GeoDataFrames
3. Set up an ortho projection for PA. The FIPS code for PA is 42.
4. Estimate some county-wide snowfall numbers
5. Merge the snowfall data into the GeoDataFrame
6. Plot the snowfall map
7. Compute Travel distance from PaMunicipalities2022_01
8. Plot the Travel Map
9. Compare and compute the total stright line travel distance around the loop using the GeoSeries.distance(), and using the haversine distance in the Platte Carree projection
