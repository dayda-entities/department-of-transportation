---
title: Multi-Modal Intelligent Traffic Signal Systems Basic Safety Message
created: '2021-01-13T19:24:17.895786'
modified: '2021-01-13T19:24:17.895794'
state: active
type: dataset
tags:
  - Anthem
  - Arizona
  - Basic Safety Message Bsm
  - Connected Vehicle Message
  - Dedicated Short Range Communication Dsrc
  - Field Test
  - Freight Signal Priority Fsp
  - I Sig
  - Intelligent Transportation Systems Its
  - Its Joint Program Office Jpo
  - Leidos
  - Map
  - Multi Modal Intelligent Traffic Signal Systems Mmitss Study
  - Roadside Equipment Rse
  - Simulation Data
  - Transit Signal Priority Tsp
groups: []
csv_url: >-
  https://data.transportation.gov/api/views/5tsh-j288/rows.csv?accessType=DOWNLOAD
json_url: >-
  https://data.transportation.gov/api/views/5tsh-j288/rows.json?accessType=DOWNLOAD
layout: post

---
The data attached and/or displayed were collected during the Multi-Modal Intelligent Transportation Signal Systems (MMITSS) study. MMITSS is a next-generation traffic signal system that seeks to provide a comprehensive traffic information framework to service all modes of transportation.

A BSM is one of the messages belonging to the Society of Automotive Engineers (SAE) J2735 Standard. This standard is geared toward supporting the interoperability of DSRC applications through the use of a standardized message set and its data frames and data elements. A BSM, which is at times referred to as a “heartbeat” message, is a frequently transmitted message (usually at approximately 10Hz) that is meant to increase a vehicle’s situational awareness. These messages are intended to be used for a variety of applications to exchange safety data regarding a vehicle’s state. 

	A typical BSM contains up to two parts. Part I, the binary large object (blob), is included in every BSM. It contains the fundamental data elements that describe a vehicle’s position (latitude, longitude, elevation) and motion (heading, speed, acceleration). Part II of a BSM contains optional data that is transmitted when required or in response to an event. Typically Part II contains data that serves as an extension of vehicle safety information (path history, path prediction, event flags) and data pertaining to the status of a vehicle’s components, such as lights, wipers, and brakes. 

NOTE: All extra attachments are located in Multi-Modal Intelligent Traffic Signal Systems Basic Safety Messages such as MAP, Detectors, and Simulation results
