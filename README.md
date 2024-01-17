# 🛰️ AutoMET - Facilitating Hands-on Activities for Satellite Meteorology Training 🌎

![rect42596](https://github.com/diegormsouza/automet/assets/54595784/e2452735-f752-44e5-9665-42438980a790)

**Developed by:** Diego Souza (https://github.com/diegormsouza) - INPE / CGCT / DISSM (Brazil)

**Objective:** The AutoMET solution (it is not a package) was created to facilitate the access and visualization of satellite imagery and products, NWP data and other meteorological information using simple functions that anyone can use and adapt, **including those not familiarized with programming**. The examples run directly in the cloud, without the need of installing any tools (but it is also possible to adapt it and run the examples locally).

**The Challenge:** During training events on satellite meteorology and related fields, we usually have a mixed audience (researchers, students, technicians, meteorologists, managers, etc). Hands-on programming activities are frequently demanded, but usually, most of the participants are not programmers, thus taking a considerable amount of time for them to be able to produce advanced images. This solution aims to create a simple way to motivate participants to learn programming by allowing them to download, process and visualize information by using simple functions. Then, if there is interest, they can understand how these functions work.

**Methodology:** Instead of going through the traditional learning steps (general programming aspects -> visualizing images -> motivation), this solution proposes another approach: visualizing images -> motivation -> general programming concepts. This new approach has proved effective in recent training events.

**Supported Datasets (Jan 2024):**

- **Geostationary Ring (EUMETVIEW):** Global mosaics (every 3 hours) with GOES-East/West, Meteosat 0°, Meteosat 45.5° and Himawari data. Data available since June 06 2021 18:00 UTC

- **GOES-East and GOES-West (AWS):** 'goes16' data available since July 10 2017, 'goes17' since August 28 2018, 'goes18' since August 02 2022. Note: please consider that goes-16 generated images every 15 minutes (instead of 10) until a few months after launch

- **Meteosat 0° and Meteosat 45.5° (EUMDAC):** 'msg0' tested with data since March 26 2004 (every 15 minutes). 'msg45' tested with data since February 01 2017.
NWP: open ecmwf data available for download since January 21 2022 00:00 ('2022-01-21 00:00'. gfs data available for download since February 26 2021 00:00 ('2021-02-26 00:00'). gfs products: 'pgrb2.0p25', 'pgrb2.0p50', 'pgrb2.1p00'.

- **METAR (UNIDATA):** metar data available for the last 10 days, for each hour

- **EUMETSAT (LAND SAF and H SAF):** A variety of products from the SAFs (Satellite Application Facilities).

**Note:** These examples were created primarily for use during capacity building activities but they can be adapted for operations as well.

Among the main packages used by Automet are:
- Pytroll/Satpy: https://github.com/pytroll/satpy 
- Herbie: https://github.com/blaylockbk/Herbie
