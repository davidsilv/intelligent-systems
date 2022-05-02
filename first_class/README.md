# Visualization of COVID-19 cases in Piauí

In this first class we learned some basic concepts about data visualization, the dataset chosen was the covid-19 in Piauí (State of Brazil), it is a public dataset and was acquired here: https://brasil.io/dataset/covid19/caso_full/
#### There are some questions we asked, the following items:
<dd>1. Filter the data to select only those referring to the state of Piauí. If a city has more than 1 sample, select the most recent one (note: dates are in descending order);</dd>
<dd>2. Plot a map with the location and number of cases;</dd>
<dd>3. Indicate the number of samples, attributes and missing data (if any) from the dataset;</dd>
<dd>4. Present descriptive statistics of non-categorical attributes;</dd>
<dd>5. Present the histograms of non-categorical attributes;</dd>
<dd>6. Capture the latitudes and longitudes for each 1 of the municipalities present in the database and add the latitude and longitude columns to the data;</dd>
<dd>7. Present a graph of latitude x longitude, where each sample will be represented by a circle and the larger the value of the estimated_population field, the larger the radius of the circle that represents that sample. The color represents the death rate (death_rate), the higher this index, the closer to red;</dd>
<dd>8. Calculate the correlation matrix;</dd>
<dd>9. Check the correlation between the death_rate attribute and the other non-categorical attributes;</dd>
</br>

**openstreetmaps** were used to capture the latitude and longitude of the 224 cities in Piauí.

The libraries that were used in this class: pandas, matplotlib, requests and folium.
