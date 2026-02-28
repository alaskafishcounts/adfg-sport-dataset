# 🐟 ADFG Sport Dataset

> **✅ DATASET UPDATED**  
> This ADF&G Sport Fish Count dataset contains 144 years of sport fishing data (1882-2025) from 64 monitoring stations across Alaska. Time format consistency fixes and manifest structure improvements have been applied.
> 
> **Last Updated:** 2026-02-28 18:35:24 UTC

**ADFG Sport Fish Count Dataset - 144 years of sport fishing data (1882-2025) across 64 locations and 10 species**

**Official fish count data from Alaska Department of Fish & Game (ADFG) monitoring stations following AFCA Location Codes Framework**

## 📊 Dataset Statistics
- **Total Files**: 3,297 JSON files
- **Total Locations**: 64 locations with data
- **ID Range**: 0-999 (AFCA Sport Framework)
- **Year Range**: 1882-2025 (144 years)
- **Species**: 10 species (Chinook, Sockeye, Coho, Pink, Chum, Steelhead, and variants)
- **Framework**: AFCA Location Codes Framework

## 🎯 About This Repository

This repository contains official fish count data from 64 monitoring stations across Alaska, operated by the Alaska Department of Fish & Game (ADF&G). The data is organized according to the official AFCA Location Codes Framework and serves as the data source for the Alaska Fish Count App.

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

## 📍 Complete Location Directory (64 Locations)

This dataset contains **64 locations** across Alaska with current sport fishing data. Each location is organized by AFCA Location Codes Framework (0-100 range).

### All Sport Fishing Locations

| Location ID | Location Name | Species Available |
|-------------|---------------|-------------------|
| 1 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/1">Auke Creek</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/1/561">steelhead</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/1/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/1/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/1/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/1/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/1/450">chum</a> |
| 5 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/5">Situk River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/5/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/5/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/5/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/5/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/5/450">chum</a> |
| 6 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/6">Gulkana River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/6/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/6/420">sockeye</a> |
| 7 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/7">Coghill River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/7/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/7/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/7/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/7/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/7/450">chum</a> |
| 8 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/8">Eshamy Creek</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/8/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/8/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/8/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/8/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/8/450">chum</a> |
| 9 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/9">Anchor River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/9/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/9/410">chinook</a> |
| 11 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/11">Deep Creek</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/11/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/11/410">chinook</a> |
| 13 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/13">Russian River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/13/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/13/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/13/450">chum</a> |
| 15 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/15">Crooked Creek</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/15/410">chinook</a> |
| 16 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/16">Little Susitna</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/16/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/16/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/16/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/16/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/16/450">chum</a> |
| 17 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/17">Deshka</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/17/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/17/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/17/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/17/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/17/450">chum</a> |
| 19 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/19">Wasilla Creek</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/19/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/19/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/19/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/19/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/19/450">chum</a> |
| 20 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/20">Cottonwood Creek</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/20/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/20/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/20/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/20/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/20/450">chum</a> |
| 21 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/21">Fish Creek</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/21/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/21/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/21/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/21/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/21/450">chum</a> |
| 22 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/22">Pauls Bay River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/22/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/22/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/22/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/22/450">chum</a> |
| 23 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/23">Afognak River (Litnik)</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/23/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/23/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/23/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/23/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/23/450">chum</a> |
| 24 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/24">Karluk River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/24/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/24/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/24/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/24/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/24/450">chum</a> |
| 25 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/25">Ayakulik River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/25/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/25/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/25/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/25/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/25/450">chum</a> |
| 26 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/26">Olga Creek (Upper Station)</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/26/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/26/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/26/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/26/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/26/450">chum</a> |
| 27 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/27">Dog Salmon River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/27/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/27/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/27/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/27/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/27/450">chum</a> |
| 28 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/28">Buskin River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/28/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/28/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/28/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/28/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/28/450">chum</a> |
| 29 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/29">Saltery Creek</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/29/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/29/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/29/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/29/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/29/450">chum</a> |
| 30 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/30">Chignik River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/30/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/30/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/30/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/30/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/30/450">chum</a> |
| 31 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/31">Orzinski Lake</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/31/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/31/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/31/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/31/450">chum</a> |
| 32 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/32">Nelson River (Sapsuk)</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/32/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/32/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/32/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/32/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/32/450">chum</a> |
| 33 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/33">Bear River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/33/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/33/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/33/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/33/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/33/450">chum</a> |
| 34 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/34">Sandy River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/34/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/34/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/34/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/34/450">chum</a> |
| 35 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/35">Ilnik River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/35/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/35/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/35/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/35/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/35/450">chum</a> |
| 37 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/37">Chena River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/37/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/37/450">chum</a> |
| 38 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/38">Salcha River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/38/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/38/450">chum</a> |
| 39 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/39">Copper River (Miles L)</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/39/420">sockeye</a> |
| 40 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/40">Kenai River (late-run sockeye)</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/40/420">sockeye</a> |
| 41 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/41">Kasilof River (sockeye)</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/41/420">sockeye</a> |
| 42 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/42">Crescent River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/42/420">sockeye</a> |
| 43 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/43">Yentna River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/43/420">sockeye</a> |
| 44 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/44">Ugashik River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/44/420">sockeye</a> |
| 45 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/45">Egegik River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/45/420">sockeye</a> |
| 46 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/46">Kvichak River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/46/420">sockeye</a> |
| 47 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/47">Alagnak River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/47/420">sockeye</a> |
| 48 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/48">Naknek River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/48/420">sockeye</a> |
| 49 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/49">Igushik River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/49/420">sockeye</a> |
| 50 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/50">Wood River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/50/420">sockeye</a> |
| 51 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/51">Nushagak River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/51/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/51/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/51/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/51/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/51/450">chum</a> |
| 52 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/52">Nuyakuk River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/52/420">sockeye</a> |
| 53 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/53">Togiak River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/53/420">sockeye</a> |
| 60 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/60">Situk River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/60/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/60/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/60/410">chinook</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/60/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/60/450">chum</a> |
| 72 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/72">Kenai River (Chinook)</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/72/411">chinook-early-run</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/72/412">chinook-late-run</a> |
| 73 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/73">Jim Creek</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/73/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/73/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/73/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/73/450">chum</a> |
| 74 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/74">McLees Lake</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/74/420">sockeye</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/74/450">chum</a> |
| 75 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/75">Ninilchik River</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/75/430">coho</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/75/410">chinook</a> |
| 76 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/76">Redoubt Lake</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/76/420">sockeye</a> |
| 77 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/77">Klag Lake</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/77/420">sockeye</a> |
| 78 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/78">Lake Creek</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/78/410">chinook</a> |
| 79 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/79">Iliuliuk River(Town Creek)</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/79/440">pink</a>, <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/79/420">sockeye</a> |
| 81 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/81">Litnik Weir</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/81/420">sockeye</a> |
| 88 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/88">Upper Station Weir</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/88/420">sockeye</a> |
| 89 | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/89">Ayakulik River Weir</a> | <a href="https://github.com/alaskafishcounts/adfg-sport-dataset/tree/master/89/420">sockeye</a> |


*This table shows all 64 locations in the sport dataset following AFCA Location Codes Framework (0-100 range). Each location folder contains species-specific subdirectories with current sport fishing data.*

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

**Last Updated:** 2026-02-28 18:35:24 UTC
**Version**: AFCA v1.0.1  
**Data Source**: Alaska Department of Fish & Game (ADF&G)  
**Framework**: AFCA Location Codes Framework  
**Repository**: alaskafishcounts/adfg-sport-dataset