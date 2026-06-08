---
title: "Data set"
---

In order to demonstrate how to work with Excel Workbooks, we provide the data as such:

[Download](https://raw.githubusercontent.com/KUBDatalab/R-EDA/main/episodes/data/flightdata.xlsx)

Data is sourced from the `nycflights13` package, and collated into the workbook. It is supplemented with 
relevant IATA codes from [datahub.io](https://datahub.io/core/airport-codes).

The `nycflights13` data is originally extracted from 
[Bureau of Transportation Statistics](https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236).

The workbook consist of four spreadsheets:

## Flights

|  Variable  |  Description/Code                               | Unit   |   
|------------|-------------------------------------------------|--------|
|  year    |  Year of departure  |        |
|  month        | Month of departure                                       |        |
|  day  | Day (of month) of departure                              |  |
|  dep_time  | Actual departure time, format HHMM or HMM in local timezone                              |  |
|  sched_dep_time    | Scheduled departure time, format HHMM or HMM in local timezone| |
|  dep_delay    | Departure delay. Negative values represent early departure| minutes   |
|  arr_time   | Actual arrival time, format HHMM or HMM in local timezone  |  |
|  sched_arr_time   |  Scheduled arrival time, format HHMM or HMM in local timezone |  |
|  arr_delay   |  Arrival delay. Negative values represent early departure | minutes |
|  carrier   | Two letter carrier abbreviation. Matches the carrier variable in "airlines"  |  |
|  flight   | Flight number   |  |
|  tailnum   | Plane tail number. Matches the tailnum variable in "planes"  |  |
|  origin   |   |  |
|  dest   |   |  |
|  air_time   |   |  |
|  distance   |   |  |
|  hour   |   |  |
|  minute   |   |  |
|  time_hour   |   |  |

## airlines

|  Variable  |  Description/Code                               | 
|------------|-------------------------------------------------|
|  carrier    |  Two letter abbreviation of the carrier. Matches the carrier variable in "flights"  |       
|  name        | Full name of the carrier                                        |        

## planes

|  Variable  |  Description/Code                               | Unit   |   
|------------|-------------------------------------------------|--------|
|  tailnum    |    |        |
|  year        |                                        |        |
|  type  |                               | |
|  manufacturer  |                               | |
|  model  |                               | |
|  engines  |                               | |
|  seats  |                               | |
|  speed  |                               | |
|  engine  |                               | |

## iata_codes

|  Variable  |  Description/Code                               | Unit   |   
|------------|-------------------------------------------------|--------|
|  iata_code    |    |        |
|  ident    |    |        |
|  type    |    |        |
|  name    |    |        |
|  elevation_ft    |    |        |
|  continent    |    |        |
|  iso_country    |    |        |
|  iso_region    |    |        |
|  municipality    |    |        |
|  icao_code    |    |        |
|  gps_code    |    |        |
|  local_code    |    |        |
|  lat    |    |        |
|  long    |    |        |