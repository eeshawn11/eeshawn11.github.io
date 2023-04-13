---
layout: single
title:  HDB Resale Dashboard
date:   2023-03-02 10:00:00 +0800
classes: wide
permalink: /hdb-resale/
excerpt: Custom excerpt here.
tags: pandas streamlit plotly vega-altair dashboard
---

{% include figure image_path="../assets/images/hdb_screenshot.png" alt="Dashboard screen capture" %}

An exploration of data retrieved from [Data.gov.sg](https://data.gov.sg/dataset/resale-flat-prices), in particular HDB resale prices from 2012, to create an interactive dashboard. I am also hopeful that any insights gleaned could be helpful to my own HDB purchase journey, but no fancy prediction model here (yet?), just some charts and maps.

This is an ongoing project to document my learning with using Streamlit and various Python libraries. While such a dashboard could perhaps be more easily created using PowerBI or Tableau, I am also taking the opportunity to explore the various Python plotting libraries and understand their documentation.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://eeshawn-hdb-resale.streamlit.app/)

**Skills Demonstrated:**

- Data extraction through live Data.gov.sg API
- Data transformation with `pandas`
- Working with geospatial data using OneMap [API](https://www.onemap.gov.sg/docs/), `Shapely` and `Mapbox`
- Data visualisation with `Vega-Altair` and `Plotly`
- Web app deployment with `streamlit`