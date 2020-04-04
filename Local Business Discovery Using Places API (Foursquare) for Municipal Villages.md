# Local Business Discovery Using Places API (Foursquare) for Municipal Villages of Special Capital Province Jakarta


A Capstone Project Report submitted to Coursera [Applied Data Science Capstone Course](https://www.coursera.org/learn/applied-data-science-capstone/home/welcome), the final course of [Applied Data Science Specialization](https://www.coursera.org/specializations/applied-data-science).

Submitted by Roysepta Abimanyu

## 01 INTRODUCTION
The detection of new businesses is an area of improvements for Kelurahan (Municipal Village) government authority.
As the central government policy to relax the issuance of business license, it is not required for the business owner to have survey visits from borough authority. This will have consequence in the enforcement of many of the Provincial regulations, including consumption tax, sanitation and hygiene, building standards, among other things.
This proposal views that pertinent officials in the Kelurahan dan Kecamantan (that supervises Kelurahan) level of government can find better solution to address this
### Current/Existing Solution
The current solution is to do patrols by the city order enforcer, a specific policing agency that is structured to the Kelurahan (Municipal Village authority). That proves to be time consuming and resourced constrained, as a Kelurahan's population can reach more than fifty thousands of people.
The other way to discover local business is to use search in Google Search and Google Maps manually and then do visit to the venue. Based on previous observation, this seems to not happens as there seems to be lack of capacity in ICT.
### Proposed Solution
If a Kecamatan  and Kelurahan authorities can detect new business by other means, this will be more efficient both to the Kecamatan and business owners. The use of consumer-generated data when they start the opening of business, through platform such as Foursquare and Google. This process can be linked to the dashboard of a Kecamatan. 
An officer of the Kecamatan can start to file and investigate whether the required business information related to taxes, health, and so on are fulfilled, and if not satisfactory, the officer can use the geolocation data to dispatch a visit the business place. As it is implemented through a database and dashboard system, the dispatches can be more systematic and can be integrated into the office's Key Performance Indicators (KPI), in order to measure the increased effectiveness.

## 02 DATASETS
The first dataset being used here is the coordinates of offices of One Door Service of the Special Capital Province of Jakarta (structured down to Kelurahan or Municipal Villages level), as provided [here](http://data.jakarta.go.id/dataset/data-lokasi-kantor-pelayanan-bptsp "here") or [here](https://github.com/rabimanyu/Coursera_Capstone/blob/master/Data-Lokasi-Kantor-Pelayanan-BPTSP-2016.csv "here"). This data dated from 2016, but still relevant as government offices are rarely moved.
The second dataset will be generated from Foursquare. However it should be noted as the platform is the least used in Indonesia. For the purpose of testing the theory of mapping and clustering of location and tied to Kelurahan offices data, this will be useful.
The other datasets that is possible to be used is Google and Instagram/Facebook, as the most popular data platform in Indonesia. If the use of Foursquare data is successful, this will be adapted to another scale when using Google or Instagram/Facebook.
Both datasets consists of places data (name of venue, name of office, address of venue, address of office, and coordinates: latitude, longitude). This will be reviewed visually with a map rendered by Folium. The next step the data will be clustered by K-Means with scikit-learn library.


## 03 METHODOLOGY

## 04 RESULTS

## 05 DISCUSSION AND RECOMMENDATIONS

## 06 CONCLUSION