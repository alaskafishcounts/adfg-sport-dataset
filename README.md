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

### 📋 AFCA Location Codes Framework (Sport: 0-999)

This dataset follows the official AFCA Location Codes Framework for sport fishing locations:

#### Location ID Range: 0-999
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

This dataset contains **57 locations** across Alaska with current sport fishing data. Each location is organized by AFCA Location Codes Framework (0-999 range).

### All Sport Fishing Locations

| Location ID | Location Name | Species Available | GitHub Folder |
|-------------|---------------|-------------------|---------------|
| 1 | Auke Creek | chinook, sockeye, coho, pink, chum, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/1) |
| 5 | Situk River | chinook, sockeye, coho, pink, chum, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/5) |
| 6 | Gulkana River | chinook, sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/6) |
| 7 | Coghill River | chinook, sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/7) |
| 8 | Eshamy Creek | chinook, sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/8) |
| 9 | Anchor River | chinook, coho, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/9) |
| 11 | Deep Creek | chinook, coho | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/11) |
| 13 | Russian River | chinook, sockeye, coho, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/13) |
| 15 | Crooked Creek | chinook | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/15) |
| 16 | Little Susitna | chinook, sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/16) |
| 17 | Deshka | chinook, sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/17) |
| 19 | Wasilla Creek | chinook, sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/19) |
| 20 | Cottonwood Creek | chinook, sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/20) |
| 21 | Fish Creek | chinook, sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/21) |
| 22 | Pauls Bay River | sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/22) |
| 23 | Afognak River (Litnik) | chinook, sockeye, coho, pink, chum, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/23) |
| 24 | Karluk River | chinook, sockeye, coho, pink, chum, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/24) |
| 25 | Ayakulik River | chinook, sockeye, coho, pink, chum, sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/25) |
| 26 | Olga Creek (Upper Station) | chinook, sockeye, coho, pink, chum, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/26) |
| 27 | Dog Salmon River | chinook, sockeye, coho, pink, chum, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/27) |
| 28 | Buskin River | chinook, sockeye, coho, pink, chum, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/28) |
| 29 | Saltery Creek | chinook, sockeye, coho, pink, chum, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/29) |
| 30 | Chignik River | chinook, sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/30) |
| 31 | Orzinski Lake | chinook, sockeye, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/31) |
| 32 | Nelson River (Sapsuk) | chinook, sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/32) |
| 33 | Bear River | chinook, sockeye, coho, pink, chum, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/33) |
| 34 | Sandy River | sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/34) |
| 35 | Ilnik River | chinook, sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/35) |
| 37 | Chena River | chinook, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/37) |
| 38 | Salcha River | chinook, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/38) |
| 39 | Copper River (Miles L) | chinook | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/39) |
| 40 | Kenai River (late-run sockeye) | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/40) |
| 41 | Kasilof River (sockeye) | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/41) |
| 42 | Crescent River | chinook | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/42) |
| 43 | Yentna River | chinook | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/43) |
| 44 | Ugashik River | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/44) |
| 45 | Egegik River | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/45) |
| 46 | Kvichak River | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/46) |
| 47 | Alagnak River | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/47) |
| 48 | Naknek River | sockeye | [Sport](https://twitter.com/alaskafishcounts/adfg-sport-dataset/tree/master/48) |
| 49 | Igushik River | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/49) |
| 50 | Wood River | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/50) |
| 51 | Nushagak River | chinook, sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/51) |
| 52 | Nuyakuk River | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/52) |
| 53 | Togiak River | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/53) |
| 60 | Situk River | chinook, sockeye, coho, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/60) |
| 72 | Kenai River (Chinook) | chinook, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/72) |
| 73 | Jim Creek | chinook, sockeye, pink, chum | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/73) |
| 74 | McLees Lake | chinook, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/74) |
| 75 | Ninilchik River | chinook, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/75) |
| 76 | Redoubt Lake | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/76) |
| 77 | Klag Lake | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/77) |
| 78 | Lake Creek | chinook | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/78) |
| 79 | Iliuliuk River(Town Creek) | chinook, steelhead | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/79) |
| 81 | Litnik Weir | chinook | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/81) |
| 88 | Upper Station Weir | sockeye | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/88) |
| 89 | Ayakulik River Weir | chinook | [Sport](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/89) |

*This table shows all 57 locations in the sport dataset following AFCA Location Codes Framework (0-999 range). Each location folder contains species-specific subdirectories with current sport fishing data.*

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

The locations are organized by AFCA management areas:

- **Southcentral Alaska (0-199)**: Kenai Peninsula, Cook Inlet, Mat-Su Valley
- **Southeast Alaska (200-399)**: Juneau, Ketchikan, Sitka areas  
- **Interior Alaska (400-599)**: Fairbanks, Denali, Yukon areas
- **Southwest Alaska (600-799)**: Bristol Bay, Kodiak, Aleutian areas
- **Arctic Alaska (800-999)**: North Slope, Arctic Coast areas

## 🔄 Related Datasets

- **Commercial Dataset**: Commercial fishing data (1000-1999 range)
- **SASAP Dataset**: Historical escapement data (2000-2999 range)
- **Sport Dataset**: Current sport fishing data (0-999 range) - *This dataset*

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