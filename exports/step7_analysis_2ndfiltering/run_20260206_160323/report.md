# Step 7 - 4check gated energy min/max report
- Generated: 2026-02-06T16:12:38
- Input: `C:\Users\jo73vure\Desktop\powerPlantProject\data\active_json`
- Output: `C:\Users\jo73vure\Desktop\powerPlantProject\exports\step7_analysis_2ndfiltering\run_20260206_160323`
- Files: **78**
- Entries seen total: **7252417**
- Entries kept total: **294561**

## Limits used
- `power_kw_min`: `None`
- `power_kw_max`: `None`
- `commissioning_date_min`: `None`
- `commissioning_date_max`: `None`

## Drop totals
- `invalid_entry`: **0**
- `not_list_json`: **0**
- `no_point`: **6956248**
- `no_state_polygon`: **237**
- `missing_bundesland`: **0**
- `missing_gemeindeschluessel`: **0**
- `triple_mismatch`: **1355**
- `no_landkreis_match`: **16**
- `missing_power`: **0**
- `user_limits`: **0**

## Output files
- `per_file.csv`
- `energy_type_minmax.csv`
- `energy_type_minmax.json`
- `summary.json`

## Energy type min/max (quick view)
- Biogas - Biogas (2493): min=30.9 kW (year=2012, BL=1402), max=99720.0 kW (year=2004, BL=1414)
- Druckentspannung (BHKW, Mischform) - Pressure Relief (Waste Pressure, CHP) (2957): min=50.0 kW (year=2014, BL=1403), max=70.0 kW (year=2015, BL=1402)
- Druckentspannung (kleinere Anlagen) - Pressure Relief (Small-scale Plants) (2958): min=32.0 kW (year=1995, BL=1402), max=55.0 kW (year=1993, BL=1402)
- Druckentspannung - Pressure Relief Energy (2406): min=50.0 kW (year=2019, BL=1402), max=5200.0 kW (year=2002, BL=1412)
- Klärgas - Sewage Gas (2405): min=50.0 kW (year=2008, BL=1402), max=4400.0 kW (year=1996, BL=1405)
- Photovoltaik - Photovoltaics (2495): min=30.005 kW (year=2006, BL=1402), max=162262.2 kW (year=2024, BL=1413)
- Stromspeicher - Battery Energy Storage (2496): min=30.16 kW (year=2023, BL=1403), max=22000.0 kW (year=2018, BL=1400)
- Tiefe Geothermie - Deep Geothermal Energy (2403): min=550.0 kW (year=2009, BL=1402), max=7000.0 kW (year=2012, BL=1403)
- Wasserkraft - Hydropower (2498): min=30.5 kW (year=1958, BL=1403), max=40000.0 kW (year=2022, BL=1403)
- Windenergie Onshore - Onshore Wind Energy (2497): min=30.4 kW (year=2016, BL=1411), max=8000.0 kW (year=2017, BL=1404)
