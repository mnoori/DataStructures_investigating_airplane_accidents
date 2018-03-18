# Airline Accidents

In this project, I'll working with a dataset that contains `77282` aviation accidents that occurred in the US and their associated metadata. You can download the file [here]. Here's the beginning of the file:

```python
Event Id | Investigation Type | Accident Number | Event Date | Location | Country | Latitude | Longitude | Airport Code | Airport Name | Injury Severity | Aircraft Damage | Aircraft Category | Registration Number | Make | Model | Amateur Built | Number of Engines | Engine Type | FAR Description | Schedule | Purpose of Flight | Air Carrier | Total Fatal Injuries | Total Serious Injuries | Total Minor Injuries | Total Uninjured | Weather Condition | Broad Phase of Flight | Report Status | Publication Date |
20150908X74637 | Accident | CEN15LA402 | 09/08/2015 | Freeport, IL | United States | 42.246111 | -89.581945 | KFEP | albertus Airport | Non-Fatal | Substantial | Unknown | N24TL | CLARKE REGINALD W | DRAGONFLY MK |  |  |  | Part 91: General Aviation |  | Personal |  |  | 1 |  |  | VMC | TAKEOFF | Preliminary | 09/09/2015 |
```

Each row represents a single aviation accident, and contains descriptive data about the accident. Here are descriptions of some of the columns:

- Event Id -- the unique id of the incident.
- Investigation Type -- what kind of investigation the NTSB conducted.
- Event Date -- the date of the accident.
- Location -- where the accident occurred.
- Country -- the country where the accident occurred.
- Latitude -- the latitude of the accident.
- Longitude -- the longitude of the accident.
- Injury Severity -- How severe the injuries were, if any.
- Aircraft Damage -- the extent of the damage to the aircraft.
- Aircraft Category -- the type of aircraft.
- Make -- the make of the aircraft.
- Model -- the model of the aircraft.
- Number of Engines -- the number of engines on the plane.
- Air Carrier -- the carrier operating the aircraft.
- Total Fatal Injuries -- the number of fatal injuries.
- Total Serious Injuries -- the number of serious injuries.
- Total Minor Injuries -- the number of minor injuries.
- Total Uninjured -- the number of people who weren't injured.
- Broad Phase of Flight -- the phase of flight in which the accident occurred.

## Goal: to utilize data structure concepts for analyzing this dataset.

[here]: http://catalog.data.gov/dataset/aviation-data-and-documentation-from-the-ntsb-accident-database-system-05748/resource/4b1e95fe-91a7-4112-85fa-424d2672a906
