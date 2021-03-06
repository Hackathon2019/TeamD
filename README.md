# Sustainable Cities and Communities

> Make cities inclusive, safe, resilient and sustainable
>
> Cities are hubs for ideas, commerce, culture, science, productivity, social development and much more. At their best, cities have enabled people to advance socially and economically. With the number of people living within cities projected to rise to 5 billion people by 2030, it’s important that efficient urban planning and management practices are in place to deal with the challenges brought by urbanization.

Follow the link to read more from the UN: [Sustainable Cities and Communities]

## Dataset Summary
Hazardous air pollutants, also known as toxic air pollutants or air toxics, are those pollutants that are known or suspected to cause cancer or other serious health effects, such as reproductive effects or birth defects, or adverse environmental effects. The Environmental Protection Agency (EPA) tracks 187 air pollutants.

The daily summary file contains data for every monitor (sampled parameter) in the Environmental Protection Agency (EPA) database for each day. This file will contain a daily summary record that is: 1. The aggregate of all sub-daily measurements taken at the monitor. 2. The single sample value if the monitor takes a single, daily sample (e.g., there is only one sample with a 24-hour duration). In this case, the mean and max daily sample will have the same value.

## Dataset Download and Information
| Link                     | Description |
| ------------------------ | ----------- |
| [Dataset and DB Backups] | This links you to a Google Drive where all of the data CSVs have been placed along with a MySQL and PostgresSQL backup. |
| [EPA HAP]                | Link to the EPA's site on Hazardous Air Pollutants (HAP). |

Descriptions for each of the columns on the CSV:  

| Column Name                                | Description |
| ------------------------------------------ | ----------- |
| County Code         | The FIPS code of the county in which the monitor resides. |
| Site Num            | A unique number within the county identifying the site. |
| Parameter Code      | The AQS code corresponding to the parameter measured by the monitor. |
| POC                 | This is the “Parameter Occurrence Code” used to distinguish different instruments that measure the same parameter at the same site. |
| Latitude            | The monitoring site’s angular distance north of the equator measured in decimal degrees. |
| Longitude           | The monitoring site’s angular distance east of the prime meridian measured in decimal degrees. |
| Datum               | The Datum associated with the Latitude and Longitude measures. |
| Parameter Name      | The name or description assigned in AQS to the parameter measured by the monitor. Parameters may be pollutants or non-pollutants. |
| Sample Duration     | The length of time that air passes through the monitoring device before it is analyzed (measured). So, it represents an averaging period in the atmosphere (for example, a 24-hour sample duration draws ambient air over a collection filter for 24 straight hours). For continuous monitors, it can represent an averaging time of many samples (for example, a 1-hour value may be the average of four one-minute samples collected during each quarter of the hour). |
| Pollutant Standard  | A description of the ambient air quality standard rules used to aggregate statistics. |
| Date Local          | The calendar date for the summary. All daily summaries are for the local standard day (midnight to midnight) at the monitor. |
| Units of Measure    | The unit of measure for the parameter. QAD always returns data in the standard units for the parameter. Submitters are allowed to report data in any unit and EPA converts to a standard unit so that we may use the data in calculations. |
| Event Type          | Indicates whether data measured during exceptional events are included in the summary. A wildfire is an example of an exceptional event; it is something that affects air quality, but the local agency has no control over. No Events means no events occurred. Events Included means events occurred and the data from them is included in the summary. Events Excluded means that events occurred but data form them is excluded from the summary. Concurred Events Excluded means that events occurred but only EPA concurred exclusions are removed from the summary. If an event occurred for the parameter in question, the data will have multiple records for each monitor. |
| Observation Count   | The number of observations (samples) taken during the day. |
| Observation Percent | The percent representing the number of observations taken with respect to the number scheduled to be taken during the day. This is only calculated for monitors where measurements are required (e.g., only certain parameters). |
| Arithmetic Mean     | The average (arithmetic mean) value for the day. |
| 1st Max Value       | The highest value for the day. |
| 1st Max Hour        | The hour (on a 24-hour clock) when the highest value for the day (the previous field) was taken. |
| AQI                 | The Air Quality Index for the day for the pollutant, if applicable. |
| Method Code         | An internal system code indicating the method (processes, equipment, and protocols) used in gathering and measuring the sample. The method name is in the next column. |
| Method Name         | A short description of the processes, equipment, and protocols used in gathering and measuring the sample. |
| Local Site Name     | The name of the site (if any) given by the State, local, or tribal air pollution control agency that operates it. |
| Address             | The approximate street address of the monitoring site.
| State Name          | The name of the state where the monitoring site is located. |
| County Name         | The name of the county where the monitoring site is located. |
| City Name           | The name of the city where the monitoring site is located. This represents the legal incorporated boundaries of cities and not urban areas. |
| CBSA Name           | The name of the core bases statistical area (metropolitan area) where the monitoring site is located.|
| Date of Last Change | The date the last time any numeric values in this record were updated in the AQS data system. |

## Team Repository Links
[SCC-C1]  
[SCC-C2]  
[SCC-C3]  
[SCC-C4]  
[SCC-C5]  
[SCC-C6]  
[SCC-C7]  
[SCC-C8]  
[SCC-P1]  
[SCC-P2]  
[SCC-P3]  

[SCC-C1]: https://github.com/CharlestonDigitalHubHackathon/SCC-C1
[SCC-C2]: https://github.com/CharlestonDigitalHubHackathon/SCC-C2
[SCC-C3]: https://github.com/CharlestonDigitalHubHackathon/SCC-C3
[SCC-C4]: https://github.com/CharlestonDigitalHubHackathon/SCC-C4
[SCC-C5]: https://github.com/CharlestonDigitalHubHackathon/SCC-C5
[SCC-C6]: https://github.com/CharlestonDigitalHubHackathon/SCC-C6
[SCC-C7]: https://github.com/CharlestonDigitalHubHackathon/SCC-C7
[SCC-C8]: https://github.com/CharlestonDigitalHubHackathon/SCC-C8
[SCC-P1]: https://github.com/CharlestonDigitalHubHackathon/SCC-P1
[SCC-P2]: https://github.com/CharlestonDigitalHubHackathon/SCC-P2
[SCC-P3]: https://github.com/CharlestonDigitalHubHackathon/SCC-P3
[Sustainable Cities and Communities]: https://www.un.org/sustainabledevelopment/cities/
[Dataset and DB Backups]: https://drive.google.com/drive/folders/1FJmy9_jKhsvj1Z3MJdk_YudBxnjJe8Kz?usp=sharing
[EPA HAP]: https://www.epa.gov/haps

