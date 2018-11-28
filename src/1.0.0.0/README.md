# Voyager1 Local Data Dictionary

The Voyager 1 dictionary contains classes that describe aspects of the Voyager 1 mission and related instruments.

Version: 1.0.0.0  
Steward: ppi

## Classes

### Voyager1
The VG1 class is the container for mission-specific metadata elements.

Attribute    | Min Occur. | Max Occur.
------------ | ---------- | -----------
[mission_phase_name](#mission_phase_name) | 0 | 1
[spacecraft_clock_start_count](#spacecraft_clock_start_count) | 0 | 1
[spacecraft_clock_stop_count](#spacecraft_clock_stop_count) | 0 | 1
## Attributes


### mission_phase_name
The mission_phase_name attribute provides the mission-defined name of a mission phase.

Type: ASCII_Short_String_Collapsed  
Units: undefined  

**Permissible Values**

Name                                    | Description
--------------------------------------- | ----------------------------
Launch | 1977-09-05 (1977-248) to 1977-09-05 (1977-248)
Earth-Jupiter Cruise | )1977-09-05 (1977-248) to 1979-01-06 (1979-006)
Jupiter Encounter | 1979-01-06 (1979-006) to 1979-04-13 (1979-103)
Jupiter-Saturn Cruise | 1979-04-13 (1979-103) to 1980-08-22 (1980-235)
Saturn Encounter | 1980-08-22 (1980-235) to 1980-12-14 (1980-349)
Interstellar Mission | 1980-12-14 (1980-349)to UNK


### spacecraft_clock_start_count
The spacecraft_clock_start_count attribute provides the value 
		of the spacecraft clock at the beginning of a time period of 
		interest.

Type: ASCII_Short_String_Collapsed  
Units: undefined  



### spacecraft_clock_stop_count
The spacecraft_clock_stop_count attribute provides the value of the spacecraft 
		clock at the beginning of a time period of interest.

Type: ASCII_Short_String_Collapsed  
Units: undefined  


