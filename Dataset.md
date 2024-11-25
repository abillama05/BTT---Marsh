# Dataset Information

### **Column Info for Hurricane Dataset**

1. **Year**: The year when the hurricane or storm data was recorded.
2. **Time**: The specific time (usually in UTC) when the data was recorded.
3. **Storm Name/Record Identifier**: The name of the storm or a unique identifier for the record.
4. **Number of Entries/Status**: Indicates the number of data entries related to a specific storm or the current status of the storm (e.g., tropical storm, hurricane).
5. **Latitude**: The latitude coordinate of the storm's location at the recorded time.
6. **Longitude**: The longitude coordinate of the storm's location at the recorded time.
7. **Maximum Sustained Wind**: The maximum sustained wind speed of the storm, typically measured in knots.
8. **Minimum Pressure**: The minimum atmospheric pressure recorded for the storm, usually measured in millibars (mb).
9. **34-knot Wind Radii NE/SE/SW/NW**: The distance from the storm's center to the outer edge of the 34-knot wind speed in the respective quadrant (northeast, southeast, southwest, northwest).
10. **50-knot Wind Radii NE/SE/SW/NW**: The distance from the storm's center to the outer edge of the 50-knot wind speed in the respective quadrant.
11. **64-knot Wind Radii NE/SE/SW/NW**: The distance from the storm's center to the outer edge of the 64-knot wind speed in the respective quadrant.

---

### **Column Info for Vessel Dataset**

1. **MMSI**: The Maritime Mobile Service Identity, a unique identifier for vessels used in AIS (Automatic Identification System) communications.
2. **BaseDateTime**: The timestamp indicating when the data was recorded.
3. **LAT**: The latitude coordinate of the vessel's location at the recorded time.
4. **LON**: The longitude coordinate of the vessel's location at the recorded time.
5. **SOG**: Speed Over Ground, the vessel's speed relative to the ground, typically measured in knots.
6. **COG**: Course Over Ground, the vessel’s direction of travel relative to the earth’s surface, usually in degrees.
7. **Heading**: The direction in which the vessel's bow is pointing, usually in degrees. This may differ from COG if the vessel is drifting.
8. **VesselName**: The name of the vessel.
9. **IMO**: The International Maritime Organization number, a unique identifier for ships, assigned by the IMO.
10. **CallSign**: The vessel's radio call sign, used for communication.
11. **VesselType**: The type or category of the vessel (e.g., cargo ship, tanker, passenger ship).
12. **Status**: The current operational status of the vessel (e.g., anchored, underway, moored).
13. **Length**: The length of the vessel, measured in meters.
14. **Width**: The width (or beam) of the vessel, also measured in meters.
15. **Draft**: The depth of water needed for the vessel to float, indicating how much of the vessel is submerged.
16. **Cargo**: Information about the type of cargo the vessel is carrying, if applicable.
17. **TransceiverClass**: The AIS transceiver class installed on the vessel (e.g., Class A for larger vessels, Class B for smaller vessels), affecting the range and frequency of AIS signals.
