# 🐟 ADFG Sport Dataset

**ADFG Sport Fish Count Dataset - 144 years of sport fishing data (1882-2025) across 57 locations and 6 species**

**Official fish count data from Alaska Department of Fish & Game (ADFG) monitoring stations following AFCA Location Codes Framework**

## 📊 Dataset Statistics
- **Total Files**: 502 (estimated based on manifest structure)
- **Total Locations**: 57
- **ID Range**: 0-999 (AFCA Sport Framework)
- **Year Range**: 1882-1885
- **Species**: 6 (Chinook, Sockeye, Coho, Pink, Chum, Steelhead)
- **Framework**: AFCA Location Codes Framework

## 🎯 About This Repository

This repository contains official fish count data from 57 monitoring stations across Alaska, operated by the Alaska Department of Fish & Game (ADF&G). The data is organized according to the official AFCA Location Codes Framework and serves as the data source for the Alaska Fish Count App.

### 📋 AFCA Location Codes Framework (Sport: 0-100)

This dataset follows the official AFCA Location Codes Framework for sport fishing locations:

#### Location ID Range: 0-100 (current)
- Reserved for expansion: 200-999 (not currently assigned)

- **0-199**: Southcentral Alaska (Kenai Peninsula, Cook Inlet, Mat-Su Valley)
- **200-399**: Southeast Alaska (Juneau, Ketchikan, Sitka areas)
- **400-599**: Interior Alaska (Fairbanks, Denali, Yukon areas)
- **600-799**: Southwest Alaska (Bristol Bay, Kodiak, Aleutian areas)
- **800-999**: Arctic Alaska (North Slope, Arctic Coast areas)

## 📁 Repository Structure

```
adfg-sport-dataset/
├── manifest.json          # Dataset manifest and metadata
├── README.md             # This documentation
├── 1/                    # Location ID 1 (Auke Creek)
│   ├── 410/              # Species ID 410 (Chinook Salmon)
│   │   ├── 2002-auke-creek-chinook.json
│   │   └── ...
│   ├── 420/              # Species ID 420 (Sockeye Salmon)
│   │   └── ...
│   └── ...
├── 5/                    # Location ID 5 (Situk River)
│   └── ...
└── ...                   # Additional locations (up to 89)
```

### 📋 File Naming Convention

- **Format**: `YEAR-location-slug-species-slug.json`
- **Example**: `2002-auke-creek-chinook.json`
- **Location Slug**: Lowercase, hyphenated location name
- **Species Slug**: Lowercase, hyphenated species name

## 🐟 Supported Species

| Species ID | Common Name           | Scientific Name            | Color Code    |
| ---------- | --------------------- | -------------------------- | ------------- |
| 410        | Chinook Salmon (King) | _Oncorhynchus tshawytscha_ | Blue          |
| 420        | Sockeye Salmon (Red)  | _Oncorhynchus nerka_       | Red           |
| 430        | Coho Salmon (Silver)  | _Oncorhynchus kisutch_     | Green         |
| 440        | Pink Salmon (Humpy)   | _Oncorhynchus gorbuscha_   | Pink          |
| 450        | Chum Salmon (Dog)     | _Oncorhynchus keta_        | Yellow/Orange |
| 561        | Steelhead Trout       | _Oncorhynchus mykiss_      | Purple        |

## 📍 Complete Location Directory (57 Locations)

This dataset contains **57 locations** across Alaska with current sport fishing data. Each location is organized by AFCA Location Codes Framework (0-100 range).

### All Sport Fishing Locations

| Location ID | Location Name | Species Available |
|-------------|---------------|-------------------|

*This table shows all 57 locations in the sport dataset following AFCA Location Codes Framework (0-100 range). Each location folder contains species-specific subdirectories with current sport fishing data.*

## 📊 Data Format

All files follow the ADFG standard format with consistent column structure:

```json
{
  "COLUMNS": [
     "YEAR",
    "COUNTDATE",
    "FISHCOUNT",
    "SPECIESID",
    "COUNTLOCATIONID",
    "COUNTLOCATION",
    "SPECIES"
  ],
  "DATA": [
    [
      2002,
      "May, 26 2002 00:00:00",
      3,
      410,
      1,
      "Auke Creek",
      "Chinook"
    ]
  ],
  "metadata": {
    "location_id": 1,
    "location_name": "Auke Creek",
    "species_id": 410,
    "species_name": "Chinook Salmon",
    "year": 2002,
    "last_updated": "2025-01-28T10:00:00Z",
    "data_source": "ADF&G Sport"
  }
}
```

## 🏔️ Regional Organization

All SPORT locations use AFCA IDs 0–100. Regional grouping is not encoded in the ID range.

## 🔄 Related Datasets

- **Commercial Dataset**: Commercial fishing data (1000-1999 range)
- **SASAP Dataset**: Historical escapement data (2000-2999 range)
- **Sport Dataset**: Current sport fishing data (0-100 range) - *This dataset*

## 📄 License & Attribution

This data is in the **Public Domain** and available for unrestricted use.

When using this data, please attribute:
- **Data Source**: Alaska Department of Fish & Game (ADF&G)
- **Repository**: alaskafishcounts/adfg-sport-dataset
- **Application**: Alaska Fish Count App
- **Framework**: AFCA Location Codes Framework

## 📞 Contact Support

- **GitHub Issues**: Report problems via repository Issues
- **Data Source**: Alaska Department of Fish & Game
- **Repository**: alaskafishcounts/adfg-sport-dataset

---

**Last Updated**: January 28, 2025  
**Version**: AFCA v1.0.1  
**Data Source**: Alaska Department of Fish & Game (ADF&G)  
**Framework**: AFCA Location Codes Framework  
**Repository**: alaskafishcounts/adfg-sport-dataset