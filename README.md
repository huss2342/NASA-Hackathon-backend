# NASA Farm Navigators - Backend

## Overview
Backend service for NASA Farm Navigators, an educational game that integrates NASA Earth Science data into interactive farming scenarios. Provides data processing, game state management, and NASA API integration.

## Core Responsibilities
- **NASA Data Integration** - Fetch and process satellite data from NASA APIs
- **Data Transformation** - Convert raw NASA datasets into game-ready formats (Soil Moisture Index, Precipitation Risk Index, Surface Temperature, NDVI)
- **Game Logic Engine** - Validate player decisions against data thresholds and calculate outcomes
- **State Management** - Track player progress, resource levels (water, money, time), and scenario completion

## Data Sources
- **SMAP (Soil Moisture Active Passive)** - Soil moisture and health indices
- **NASA Flood Data Pathfinder** - Precipitation forecasts and flood risk
- **MODIS/VIIRS** - Surface temperature and heat stress data
- **NDVI Datasets** - Vegetation health for pest/disease detection

## Key Functions
- Process and simplify NASA data into player-friendly metrics
- Define critical thresholds for decision validation (e.g., PRI > 70% = flood risk)
- Calculate resource impacts based on player choices
- Determine win/fail conditions for each scenario
- Provide educational feedback explaining data and outcomes

## Tech Stack
- Node.js + Express

## API Endpoints
*[To be defined based on game requirements]*
