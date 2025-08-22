# Green-Space-Equity-Mapping-Urban-Environmental-Justice-Analysis
Green Space Equity Mapping: Urban Environmental Justice Analysis Project Title Green Space Equity Mapping: Measuring Access to Parks and Green Cover for Urban Environmental Justice Description This project implements a comprehensive geospatial analysis framework to measure and visualize green space equity across urban areas.
Overview
Urban green spaces are essential for public health, environmental quality, and social equity. However, access to parks and green areas is often unevenly distributed across communities, with low-income and marginalized neighborhoods frequently experiencing "green space inequity." This project provides a comprehensive toolkit for measuring, analyzing, and visualizing green space accessibility patterns to support evidence-based urban planning and environmental justice initiatives.
Features
Core Functionality

Multi-source Data Integration: Combines OpenStreetMap parks data, vegetation indices (NDVI), and population demographics
Spatial Accessibility Analysis: Calculates walking distances to parks, service area coverage, and green space density
Equity Scoring System: Develops composite metrics to identify underserved communities
Grid-based Analysis: Creates systematic spatial analysis using customizable grid cells
Interactive Visualization: Generates both static dashboards and interactive web maps

Advanced Analytics

Cluster Analysis: Groups similar neighborhoods for targeted interventions
Per Capita Calculations: Measures green space availability relative to population density
Multi-criteria Assessment: Evaluates equity using distance, quantity, and quality metrics
Scalable Framework: Adaptable to different cities and geographic scales

Technical Architecture
Data Sources

OpenStreetMap (OSM): Parks, gardens, recreational areas, and green spaces
NDVI Simulation: Vegetation density and urban canopy coverage
Population Data: Demographic distribution and density patterns
Administrative Boundaries: City limits and neighborhood definitions

Methodology

Spatial Grid Creation: Divides study area into analysis units (default: 1km x 1km)
Green Space Extraction: Identifies parks and natural areas from OSM
Accessibility Calculation: Measures distance and coverage metrics
Vegetation Analysis: Incorporates NDVI for comprehensive green cover assessment
Equity Scoring: Combines multiple indicators into composite equity index
Classification System: Categories areas from "Severely Underserved" to "Well Served"
