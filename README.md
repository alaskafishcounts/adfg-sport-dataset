# 🐟 Alaska Fish Count Data Repository

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

This repository contains data from **58+ monitoring stations** across Alaska, including:

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
