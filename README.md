# 🐟 Alaska Fish Count Data Repository

**ADFG Sport Fish Count Dataset - 86 years of sport fishing data (1939-2024) across 58+ locations and 6 species**

**Official fish count data from Alaska Department of Fish & Game (ADFG) monitoring stations**

GitHub License Data Source

## 📊 About This Repository

This repository contains official fish count data from 58+ monitoring stations across Alaska, operated by the Alaska Department of Fish & Game (ADF&G). The data is automatically synchronized from ADF&G's official sources and made available for public use.

### 🎯 Purpose

* **Public Data Access**: Provide easy access to official ADF&G fish count data
* **Application Support**: Serve as the data source for the Alaska Fish Count App
* **Research & Analysis**: Enable researchers, anglers, and the public to analyze fish populations
* **Transparency**: Ensure public access to government fish monitoring data

## 📁 Repository Structure

```
adfg-sport-dataset/
├── manifest.json          # Data index and metadata
├── README.md             # This file
├── 1/                    # Location ID 1 (e.g., Kenai River)
│   ├── 410/              # Species ID 410 (Chinook Salmon)
│   │   ├── 2025-kenai-river-chinook.json
│   │   ├── 2024-kenai-river-chinook.json
│   │   └── ...
│   ├── 420/              # Species ID 420 (Sockeye Salmon)
│   │   ├── 2025-kenai-river-sockeye.json
│   │   └── ...
│   └── ...
├── 5/                    # Location ID 5 (e.g., Russian River)
│   └── ...
└── ...                   # Additional locations

```

### 📋 File Naming Convention

* **Format**: `YEAR-location-slug-species-slug.json`
* **Example**: `2025-kenai-river-chinook.json`
* **Location Slug**: Lowercase, hyphenated location name
* **Species Slug**: Lowercase, hyphenated species name

## 🐟 Supported Species

| Species ID | Common Name           | Scientific Name            | Color Code    |
| ---------- | --------------------- | -------------------------- | ------------- |
| 410        | Chinook Salmon (King) | _Oncorhynchus tshawytscha_ | Blue          |
| 420        | Sockeye Salmon (Red)  | _Oncorhynchus nerka_       | Red           |
| 430        | Coho Salmon (Silver)  | _Oncorhynchus kisutch_     | Green         |
| 440        | Pink Salmon (Humpy)   | _Oncorhynchus gorbuscha_   | Pink          |
| 450        | Chum Salmon (Dog)     | _Oncorhynchus keta_        | Yellow/Orange |
| 561        | Steelhead Trout       | _Oncorhynchus mykiss_      | Purple        |

### 🏃 Run Types

Some species have multiple run types:

* **Early Run**: Spring/early summer arrivals
* **Late Run**: Late summer/fall arrivals
* **Mixed Run**: Combined early and late runs

## 📍 Monitoring Locations

This repository contains data from **57 monitoring stations** across Alaska, including:

### 🏔️ Major Regions

* **Southcentral Alaska**: Kenai River, Russian River, Ship Creek
* **Southeast Alaska**: Fish Creek, Montana Creek, Steep Creek
* **Interior Alaska**: Chena River, Salcha River, Clear Creek
* **Southwest Alaska**: Kvichak River, Naknek River, Alagnak River

### 🎯 Location Coverage

* **Rivers & Streams**: Primary salmon spawning habitats
* **Fish Passes**: Artificial structures for fish counting
* **Weirs**: Natural barriers used for monitoring
* **Sonar Sites**: Advanced acoustic monitoring stations

## Location Directory

This dataset contains **57 locations** across Alaska with current sport fishing data. Each location is organized by AFCA Location Codes Framework (0-999 range).

### Complete Location List (57 Locations)

| Location ID | Location Name | Species Available | GitHub Folder |
|-------------|---------------|-------------------|---------------|
| 1 | [Location 1](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/1) | chinook, sockeye, coho, pink, chum, steelhead | [1](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/1) |
| 5 | [Location 5](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/5) | chinook, sockeye, coho, pink, chum, steelhead | [5](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/5) |
| 6 | [Location 6](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/6) | chinook, sockeye | [6](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/6) |
| 7 | [Location 7](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/7) | chinook, sockeye, coho, pink, chum | [7](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/7) |
| 8 | [Location 8](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/8) | chinook, sockeye, coho, pink, chum | [8](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/8) |
| 9 | [Location 9](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/9) | chinook, coho, steelhead | [9](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/9) |
| 11 | [Location 11](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/11) | chinook, coho | [11](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/11) |
| 13 | [Location 13](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/13) | chinook, sockeye, coho, chum | [13](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/13) |
| 15 | [Location 15](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/15) | chinook | [15](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/15) |
| 16 | [Location 16](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/16) | chinook, sockeye, coho, pink, chum | [16](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/16) |
| 17 | [Location 17](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/17) | chinook, sockeye, coho, pink, chum | [17](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/17) |
| 19 | [Location 19](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/19) | chinook, sockeye, coho, pink, chum | [19](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/19) |
| 20 | [Location 20](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/20) | chinook, sockeye, coho, pink, chum | [20](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/20) |
| 21 | [Location 21](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/21) | chinook, sockeye, coho, pink, chum | [21](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/21) |
| 22 | [Location 22](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/22) | sockeye, coho, pink, chum | [22](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/22) |
| 23 | [Location 23](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/23) | chinook, sockeye, coho, pink, chum, steelhead | [23](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/23) |
| 24 | [Location 24](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/24) | chinook, sockeye, coho, pink, chum, steelhead | [24](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/24) |
| 25 | [Location 25](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/25) | chinook, sockeye, coho, pink, chum, steelhead | [25](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/25) |
| 26 | [Location 26](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/26) | chinook, sockeye, coho, pink, chum, steelhead | [26](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/26) |
| 27 | [Location 27](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/27) | chinook, sockeye, coho, pink, chum, steelhead | [27](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/27) |

*Note: This table shows the first 20 locations. The complete dataset contains 57 locations total. Each location folder contains species-specific subdirectories with current sport fishing data.*

### Regional Organization

The locations are organized by management areas:

- **Southcentral Alaska (0-199)**: Kenai Peninsula, Cook Inlet, Mat-Su Valley
- **Southeast Alaska (200-399)**: Juneau, Ketchikan, Sitka areas
- **Interior Alaska (400-599)**: Fairbanks, Denali, Yukon areas
- **Southwest Alaska (600-799)**: Bristol Bay, Kodiak, Aleutian areas
- **Arctic Alaska (800-999)**: North Slope, Arctic Coast areas

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
      1939,
      "May, 26 1939 00:00:00",
      3,
      410,
      1000,
      "Akalura Creek",
      "Chinook"
    ]
  ],
  "metadata": {
    "location_id": 1,
    "location_name": "Kenai River",
    "species_id": 420,
    "species_name": "Sockeye Salmon",
    "year": 2025,
    "last_updated": "2025-01-28T10:00:00Z",
    "data_source": "ADF&G Official"
  }
}
```

### 📈 Data Fields

* **date**: Date of the count (YYYY-MM-DD format)
* **count**: Number of fish counted on that date
* **cumulative**: Running total for the season
* **notes**: Additional information about the count

## 🔄 Data Updates

### ⏰ Update Schedule

* **Automatic**: Data is synchronized every 6 hours during peak season
* **Manual**: Updates can be triggered manually via GitHub Actions
* **Real-time**: New data appears within hours of ADF&G updates

### 📅 Seasonal Patterns

* **Spring**: Early-run Chinook and Steelhead
* **Summer**: Peak salmon runs (June-August)
* **Fall**: Late-run salmon and spawning completion
* **Winter**: Limited monitoring, data may be sparse

## 🛠️ Usage Examples

### 📱 Web Application

Visit Alaska Fish Count App for an interactive interface.

### 🔗 Direct API Access

```javascript
// Fetch manifest to discover available data
const manifest = await fetch('https://raw.githubusercontent.com/alaskafishcounts/adfg-sport-dataset/master/manifest.json')
  .then(response => response.json());

// Access specific location/species/year data
const data = await fetch('https://raw.githubusercontent.com/alaskafishcounts/adfg-sport-dataset/master/1/420/2025-kenai-river-sockeye.json')
  .then(response => response.json());
```

### 📊 Data Analysis

```python
import requests
import json

# Get manifest
manifest_url = "https://raw.githubusercontent.com/alaskafishcounts/adfg-sport-dataset/master/manifest.json"
manifest = requests.get(manifest_url).json()

# Find available data for Kenai River Sockeye
kenai_sockeye = manifest['organized']['1']['species']['420']['files']
print(f"Available years: {list(kenai_sockeye.keys())}")
```

## 🔗 Related Resources

### 🌐 Official Sources

* **ADF&G Fish Counts**: Official ADF&G fish count website
* **ADF&G Sport Fish**: Sport fishing information
* **ADF&G Commercial Fisheries**: Commercial fishing data

### 📱 Applications

* **Alaska Fish Count App**: Interactive web application
* **Mobile App**: Mobile-optimized interface
* **API Documentation**: Developer resources

### 📚 Documentation

* **Data Dictionary**: Detailed field descriptions
* **API Reference**: Technical documentation
* **User Guide**: How to use the data

## 📄 License & Attribution

### 📜 License

This data is in the **Public Domain** and available for unrestricted use.

### 🏛️ Attribution

When using this data, please attribute:

* **Data Source**: Alaska Department of Fish & Game (ADF&G)
* **Repository**: alaskafishcounts/adfg-sport-dataset
* **Application**: Alaska Fish Count App

### 📊 Citation

```
Alaska Department of Fish & Game. (2025). Fish Count Data. 
Retrieved from https://github.com/alaskafishcounts/adfg-sport-dataset
```

## 🤝 Contributing

### 🐛 Reporting Issues

* **Data Issues**: Report data problems via GitHub Issues
* **Feature Requests**: Suggest improvements for the data structure
* **Documentation**: Help improve this README or other documentation

### 🔧 Development

* **Data Pipeline**: Contribute to the automated data synchronization
* **Validation**: Help improve data quality checks
* **Documentation**: Enhance user guides and technical docs

## 📞 Support & Contact

### 🆘 Getting Help

* **GitHub Issues**: Report problems
* **Email**: support@alaskafishcounts.com
* **Documentation**: User Guide

### 📧 Contact Information

* **Project Maintainer**: Alaska Fish Count App Team
* **Data Source**: Alaska Department of Fish & Game
* **Repository**: alaskafishcounts/adfg-sport-dataset

---

**Last Updated**: January 28, 2025  
**Version**: AFCA v1.0.1  
**Data Source**: Alaska Department of Fish & Game (ADF&G)  
**Repository**: alaskafishcounts/adfg-sport-dataset


### Complete Location List

| Location ID | Location Name | Species Available | GitHub Folder |
|-------------|---------------|-------------------|---------------|
| 1 | Auke Creek | 6 | [1](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/1) |
| 5 | Situk River | 6 | [5](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/5) |
| 6 | Gulkana River | 2 | [6](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/6) |
| 7 | Coghill River | 5 | [7](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/7) |
| 8 | Eshamy Creek | 5 | [8](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/8) |
| 9 | Anchor River | 3 | [9](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/9) |
| 11 | Deep Creek | 2 | [11](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/11) |
| 13 | Russian River | 5 | [13](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/13) |
| 15 | Crooked Creek | 1 | [15](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/15) |
| 16 | Little Susitna | 5 | [16](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/16) |
| 17 | Deshka | 5 | [17](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/17) |
| 19 | Wasilla Creek | 5 | [19](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/19) |
| 20 | Cottonwood Creek | 5 | [20](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/20) |
| 21 | Fish Creek | 5 | [21](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/21) |
| 22 | Pauls Bay River | 4 | [22](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/22) |
| 23 | Afognak River (Litnik) | 6 | [23](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/23) |
| 24 | Karluk River | 6 | [24](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/24) |
| 25 | Ayakulik River | 6 | [25](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/25) |
| 26 | Olga Creek (Upper Station) | 6 | [26](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/26) |
| 27 | Dog Salmon River | 6 | [27](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/27) |
| 28 | Buskin River | 6 | [28](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/28) |
| 29 | Saltery Creek | 6 | [29](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/29) |
| 30 | Chignik River | 5 | [30](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/30) |
| 31 | Orzinski Lake | 4 | [31](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/31) |
| 32 | Nelson River (Sapsuk) | 5 | [32](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/32) |
| 33 | Bear River | 6 | [33](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/33) |
| 34 | Sandy River | 4 | [34](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/34) |
| 35 | Ilnik River | 5 | [35](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/35) |
| 37 | Chena River | 2 | [37](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/37) |
| 38 | Salcha River | 2 | [38](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/38) |
| 39 | Copper River (Miles L) | 1 | [39](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/39) |
| 40 | Kenai River (late-run sockeye) | 1 | [40](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/40) |
| 41 | Kasilof River (sockeye) | 1 | [41](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/41) |
| 42 | Crescent River | 1 | [42](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/42) |
| 43 | Yentna River | 1 | [43](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/43) |
| 44 | Ugashik River | 1 | [44](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/44) |
| 45 | Egegik River | 1 | [45](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/45) |
| 46 | Kvichak River | 1 | [46](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/46) |
| 47 | Alagnak River | 1 | [47](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/47) |
| 48 | Naknek River | 1 | [48](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/48) |
| 49 | Igushik River | 1 | [49](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/49) |
| 50 | Wood River | 1 | [50](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/50) |
| 51 | Nushagak River | 5 | [51](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/51) |
| 52 | Nuyakuk River | 1 | [52](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/52) |
| 53 | Togiak River | 1 | [53](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/53) |
| 60 | Situk River | 5 | [60](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/60) |
| 72 | Kenai River (Chinook) | 2 | [72](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/72) |
| 73 | Jim Creek | 4 | [73](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/73) |
| 74 | McLees Lake | 2 | [74](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/74) |
| 75 | Ninilchik River | 2 | [75](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/75) |
| 76 | Redoubt Lake | 1 | [76](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/76) |
| 77 | Klag Lake | 1 | [77](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/77) |
| 78 | Lake Creek | 1 | [78](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/78) |
| 79 | Iliuliuk River(Town Creek) | 2 | [79](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/79) |
| 81 | Litnik Weir | 1 | [81](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/81) |
| 88 | Upper Station Weir | 1 | [88](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/88) |
| 89 | Ayakulik River Weir | 1 | [89](https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/89) |