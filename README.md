⚠️ WARNING: Do not delete or rename this file without updating the fetch URLs in the Wandly codebase.

# TravelPlan Data Repository

## Purpose
This repository hosts country-specific data used by the [Wandly](https://wandly.cc) travel planning application.

## Contents
- `data.json` - Country information database including:
  - Electrical socket types and voltage
  - Transportation information (fuel units, driving side, speed units)
  - Emergency contact numbers
  - Tipping culture customs

## Usage
This file is fetched in real-time by the Wandly website via:
```
https://raw.githubusercontent.com/sauheb/TravelPlan/refs/heads/main/data.json
```

**⚠️ WARNING:** Do not delete or rename this file without updating the fetch URLs in the Wandly codebase.

## Data Structure
Each country entry contains:
```json
{
  "ISO_3166_1_alpha2": "US",
  "Plug Type": "A, B",
  "Voltage": "120V",
  "Frequency": "60Hz",
  "Fuel Units": "Gallons",
  "Left/Right Hand Drive": "RHT",
  "Emergency_Police": "911",
  "Tipping Culture": "15-20% expected"
}
```

## Maintenance
- Owner: Saurabh Verma
- Last Updated: [19 Oct 2025]
- Contact: [sauheb@gmail.com]

## Backup
A backup of this file is maintained at [none]

## License
Data compiled from public sources for educational/informational purposes.
