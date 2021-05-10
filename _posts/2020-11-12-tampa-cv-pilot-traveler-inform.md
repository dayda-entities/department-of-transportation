---
title: Tampa CV Pilot Traveler Information Message (TIM) Sample
created: '2020-11-12T12:49:40.787926'
modified: '2021-04-21T19:57:56.747388'
state: active
type: dataset
tags:
  - Arterial
  - Connected Vehicle Message
  - Connected Vehicle Pilot Cvp
  - Field Test
  - Florida
  - Intelligent Transportation Systems Its
  - Its Joint Program Office Jpo
  - Roadside Equipment Rse
  - Tampa
  - Tampa Connected Vehicle Pilot Deployment Tampa Cv Pilot
  - Tampa Hillsborough Expressway Authority Thea
  - Traveler Information Message Tim
groups: []
csv_url: >-
  https://data.transportation.gov/api/views/in46-gmir/rows.csv?accessType=DOWNLOAD
json_url: >-
  https://data.transportation.gov/api/views/in46-gmir/rows.json?accessType=DOWNLOAD
layout: post

---
The Tampa CV Pilot generates data from the interaction between vehicles and between vehicles and infrastructure. This dataset consists of Traveler Information Messages (TIMs) transmitted by road-side units (RSU) located throughout the Tampa CV Pilot Study area.  The full set of raw, TIM data from Tampa CV Pilot can be found in the <a href="http://usdot-its-cvpilot-public-data.s3.amazonaws.com/index.html" target="_blank">ITS Sandbox</a>. The data fields follow a SAE J2735 TIM message structure to convey important traffic information to onboard units (OBU) of equipped vehicles. Refer to SAE J2735 Section 5.16 Message: MSG_TravelerInformation Message (TIM).

This dataset holds a flattened sample of the TIM data from Tampa CV Pilot. Three additional fields were added to this Socrata dataset during ETL: a geo column (travelerdataframe_msgId_position) to allow for mapping of the geocoded TIM data within Socrata, a random number column (randomNum) to allow for random sampling of data points within Socrata, and a time of day generated column (metadata_generatedAt_timeOfDay) to allow for filtering of data by generated time.
