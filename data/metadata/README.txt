DATA PRODUCT README
===================

Title: Lake Rotoiti fixed buoy data
Version: v0.0.1
Date Created: 2025-05-30
Authors: Tadhg Moore, Chris McBride
License: CC BY 4.0

---

DESCRIPTION
-----------
This dataset contains high-frequency environmental measurements collected by a fixed sensor buoy deployed in Lake Rotoiti. The buoy was equipped with a temperature string spanning the water column, along with surface sensors for chlorophyll-a, and dissolved oxygen. Additional dissolved oxygen measurements were recorded at the lake bottom. A meteorological station mounted on the buoy recorded atmospheric conditions including wind speed, and wind direction. These observations support the characterization of physical, chemical, and biological dynamics in Lake Rotoiti over time.
---

FILES INCLUDED
--------------
- access.csv
- attributes.csv
- biblio.csv
- creators.csv
- dataspice.json
- README.txt

---

VARIABLES
---------
- site: Site of measurement [file: device_position.csv, units: NA]
- device_id: Device ID [file: device_position.csv, units: NA]
- reference: Reference point, can be either depth (d), height (h) or elevation (e) [file: device_position.csv, units: NA]
- z_relative: Relative distance from reference point [file: device_position.csv, units: NA]
- device_id: Device ID [file: device_variable.csv, units: NA]
- var_abbr: Variable abbreviation [file: device_variable.csv, units: NA]
- var_abbr: Variable abbreviation [file: qc_filters.csv, units: NA]
- low: Low value to set values to NA if they are below this value [file: qc_filters.csv, units: NA]
- high: High value to set values to NA if they are above this value [file: qc_filters.csv, units: NA]
- roc: Rate of change to set values to NA which change from the previous value by greater than this value [file: qc_filters.csv, units: NA]
- consec: Set values to NA if there are consecutive values greater than this value [file: qc_filters.csv, units: NA]
- interp: Interpolate values if there is a data gap less than this value [file: qc_filters.csv, units: NA]
- datetime: Date and time of measurement [file: rotoiti_qc.csv, units: NA]
- site: Site of measurement [file: rotoiti_qc.csv, units: NA]
- raw_value_t_wtr_d50: Raw water temperature at 0.5m [file: rotoiti_qc.csv, units: degree_Celsius]
- raw_value_t_wtr_d200: Raw water temperature at 2.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- raw_value_t_wtr_d400: Raw water temperature at 4.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- raw_value_t_wtr_d600: Raw water temperature at 6.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- raw_value_t_wtr_d900: Raw water temperature at 9.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- raw_value_t_wtr_d1200: Raw water temperature at 12.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- raw_value_t_wtr_d1500: Raw water temperature at 15.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- raw_value_t_wtr_d1810: Raw water temperature at 18.1m [file: rotoiti_qc.csv, units: degree_Celsius]
- raw_value_t_wtr_d1800: Raw water temperature at 18.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- raw_value_t_wtr_d2100: Raw water temperature at 21.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- raw_value_c_do_d100: Raw dissolved oxygen concentration at 1.0m [file: rotoiti_qc.csv, units: mg/l]
- raw_value_c_do_d1800: Raw dissolved oxygen concentration at 18.0m [file: rotoiti_qc.csv, units: mg/l]
- raw_value_c_do_sat_d100: Raw issolved oxygen percent saturation at 1.0m [file: rotoiti_qc.csv, units: percent]
- raw_value_c_do_sat_d1800: Raw dissolved oxygen percent saturation at 18.0m [file: rotoiti_qc.csv, units: percent]
- raw_value_w_spd_h150: Raw wind speed at 1.5m [file: rotoiti_qc.csv, units: m/s]
- raw_value_w_dir_h150: Raw wind direction at 1.5m [file: rotoiti_qc.csv, units: degree]
- raw_value_f_chl_d100: Raw chlorophyll fluorescence at 1.0m [file: rotoiti_qc.csv, units: RFU]
- qc_value_t_wtr_d50: Water temperature at 0.5m [file: rotoiti_qc.csv, units: degree_Celsius]
- qc_value_t_wtr_d200: Water temperature at 2.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- qc_value_t_wtr_d400: Water temperature at 4.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- qc_value_t_wtr_d600: Water temperature at 6.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- qc_value_t_wtr_d900: Water temperature at 9.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- qc_value_t_wtr_d1200: Water temperature at 12.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- qc_value_t_wtr_d1500: Water temperature at 15.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- qc_value_t_wtr_d1810: Water temperature at 18.1m [file: rotoiti_qc.csv, units: degree_Celsius]
- qc_value_t_wtr_d1800: Water temperature at 18.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- qc_value_t_wtr_d2100: Water temperature at 21.0m [file: rotoiti_qc.csv, units: degree_Celsius]
- qc_value_c_do_d100: Dissolved oxygen concentration at 1.0m [file: rotoiti_qc.csv, units: mg/l]
- qc_value_c_do_d1800: Dissolved oxygen concentration at 18.0m [file: rotoiti_qc.csv, units: mg/l]
- qc_value_c_do_sat_d100: Dissolved oxygen percent saturation at 1.0m [file: rotoiti_qc.csv, units: percent]
- qc_value_c_do_sat_d1800: Dissolved oxygen percent saturation at 18.0m [file: rotoiti_qc.csv, units: percent]
- qc_value_w_spd_h150: Wind speed at 1.5m [file: rotoiti_qc.csv, units: m/s]
- qc_value_w_dir_h150: Wind direction at 1.5m [file: rotoiti_qc.csv, units: degree]
- qc_value_f_chl_d100: Chlorophyll fluorescence at 1.0m [file: rotoiti_qc.csv, units: RFU]
- qc_code_t_wtr_d50: Quality control code for water temperature at 0.5m [file: rotoiti_qc.csv, units: NA]
- qc_code_t_wtr_d200: Quality control code for water temperature at 2.0m [file: rotoiti_qc.csv, units: NA]
- qc_code_t_wtr_d400: Quality control code for water temperature at 4.0m [file: rotoiti_qc.csv, units: NA]
- qc_code_t_wtr_d600: Quality control code for water temperature at 6.0m [file: rotoiti_qc.csv, units: NA]
- qc_code_t_wtr_d900: Quality control code for water temperature at 9.0m [file: rotoiti_qc.csv, units: NA]
- qc_code_t_wtr_d1200: Quality control code for water temperature at 12.0m [file: rotoiti_qc.csv, units: NA]
- qc_code_t_wtr_d1500: Quality control code for water temperature at 15.0m [file: rotoiti_qc.csv, units: NA]
- qc_code_t_wtr_d1810: Quality control code for water temperature at 18.1m [file: rotoiti_qc.csv, units: NA]
- qc_code_t_wtr_d1800: Quality control code for water temperature at 18.0m [file: rotoiti_qc.csv, units: NA]
- qc_code_t_wtr_d2100: Quality control code for water temperature at 21.0m [file: rotoiti_qc.csv, units: NA]
- qc_code_c_do_d100: Quality control code for dissolved oxygen concentration at 1.0m [file: rotoiti_qc.csv, units: NA]
- qc_code_c_do_d1800: Quality control code for dissolved oxygen concentration at 18.0m [file: rotoiti_qc.csv, units: NA]
- qc_code_c_do_sat_d100: Quality control code for dissolved oxygen percent saturation at 1.0m [file: rotoiti_qc.csv, units: NA]
- qc_code_c_do_sat_d1800: Quality control code for dissolved oxygen percent saturation at 18.0m [file: rotoiti_qc.csv, units: NA]
- qc_code_w_spd_h150: Quality control code for wind speed at 1.5m [file: rotoiti_qc.csv, units: NA]
- qc_code_w_dir_h150: Quality control code for wind direction at 1.5m [file: rotoiti_qc.csv, units: NA]
- qc_code_f_chl_d100: Quality control code for chlorophyll fluorescence at 1.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_t_wtr_d50: Quality control flag for water temperature at 0.5m [file: rotoiti_qc.csv, units: NA]
- qc_flag_t_wtr_d200: Quality control flag for water temperature at 2.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_t_wtr_d400: Quality control flag for water temperature at 4.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_t_wtr_d600: Quality control flag for water temperature at 6.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_t_wtr_d900: Quality control flag for water temperature at 9.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_t_wtr_d1200: Quality control flag for water temperature at 12.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_t_wtr_d1500: Quality control flag for water temperature at 15.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_t_wtr_d1810: Quality control flag for water temperature at 18.1m [file: rotoiti_qc.csv, units: NA]
- qc_flag_t_wtr_d1800: Quality control flag for water temperature at 18.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_t_wtr_d2100: Quality control flag for water temperature at 21.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_c_do_d100: Quality control flag for dissolved oxygen concentration at 1.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_c_do_d1800: Quality control flag for dissolved oxygen concentration at 18.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_c_do_sat_d100: Quality control flag for dissolved oxygen percent saturation at 1.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_c_do_sat_d1800: Quality control flag for dissolved oxygen percent saturation at 18.0m [file: rotoiti_qc.csv, units: NA]
- qc_flag_w_spd_h150: Quality control flag for wind speed at 1.5m [file: rotoiti_qc.csv, units: NA]
- qc_flag_w_dir_h150: Quality control flag for wind direction at 1.5m [file: rotoiti_qc.csv, units: NA]
- qc_flag_f_chl_d100: Quality control flag for chlorophyll fluorescence at 1.0m [file: rotoiti_qc.csv, units: NA]
- device_id: Device ID [file: sensor_calibrations.csv, units: NA]
- date: Date of calibration [file: sensor_calibrations.csv, units: NA]
- site: Site of measurement [file: sensor_calibrations.csv, units: NA]
- variable: Variable abbreviation [file: sensor_calibrations.csv, units: NA]
- temperature: Temperature at calibration [file: sensor_calibrations.csv, units: NA]
- type: Type of calibration [file: sensor_calibrations.csv, units: NA]
- comment: Comment [file: sensor_calibrations.csv, units: NA]
- device_id: Device ID [file: sensor_reference.csv, units: NA]
- date: Date of reference measurement [file: sensor_reference.csv, units: NA]
- reference_type: Type of reference (e.g. buffer, saturated water) [file: sensor_reference.csv, units: NA]
- value_actual: Value of the reference [file: sensor_reference.csv, units: NA]
- units_value: Units of the value [file: sensor_reference.csv, units: NA]
- value_measured: Measured value by the sensor [file: sensor_reference.csv, units: NA]
- units_sensor: Units of the sensor [file: sensor_reference.csv, units: NA]
- temperature: Temperature of the reference type at measurement [file: sensor_reference.csv, units: NA]
- comment: Comment [file: sensor_reference.csv, units: NA]
- device_id: Device ID [file: sensor_scaling.csv, units: NA]
- date: Date [file: sensor_scaling.csv, units: NA]
- offset: Offset applied to sensor measurement [file: sensor_scaling.csv, units: NA]
- multiplier: Multiplier applied to sensor measurement [file: sensor_scaling.csv, units: NA]
- range: Range of measurements [file: sensor_scaling.csv, units: NA]
- log_multiplier: Multiplier applied at the logger [file: sensor_scaling.csv, units: NA]
- source: Source of information [file: sensor_scaling.csv, units: NA]
- comment: Comment [file: sensor_scaling.csv, units: NA]
- site: Site of measurement [file: site_devices.csv, units: NA]
- device_id: Device ID [file: site_devices.csv, units: NA]
- date_from: Date device is deployed to site [file: site_devices.csv, units: NA]
- date_to: Date device is retrieved from site [file: site_devices.csv, units: NA]
- site: Site of measurement [file: site_events.csv, units: NA]
- date: Date [file: site_events.csv, units: NA]
- site_visit: Was the site visited, logical value [file: site_events.csv, units: NA]
- variables: List of variables or can be all [file: site_events.csv, units: NA]
- action: Type of action at site such as deployed, removed, cleaned [file: site_events.csv, units: NA]
- comments: Comment [file: site_events.csv, units: NA]
- site: Site of measurement [file: sites.csv, units: NA]
- location: Location of site [file: sites.csv, units: NA]
- type: Type of monitoring site [file: sites.csv, units: NA]
- customer: Customer [file: sites.csv, units: NA]
- lon: Longitude [file: sites.csv, units: NA]
- lat: Latitude [file: sites.csv, units: NA]
- elev: Elevation [file: sites.csv, units: NA]
- type: Type of variable [file: variables.csv, units: NA]
- abbr: Abbreviation of variable [file: variables.csv, units: NA]
- full_text: Full text variable name [file: variables.csv, units: NA]
- parsed: Variable name to be parsed [file: variables.csv, units: NA]
- label: Label for variable [file: variables.csv, units: NA]

---

USAGE
-----
Cite the dataset as:
[Add citation here]

License:
This dataset is shared under a CC BY 4.0 license. See `data/metadata/access.csv` for details.

Contact:
Tadhg Moore – tadhg@limnotrack.com
