# 🛰️ AutoMET - Facilitating Hands-on Activities for Satellite Meteorology Training 🌎

![rect42596](https://github.com/diegormsouza/automet/assets/54595784/e2452735-f752-44e5-9665-42438980a790)

**Introduction:** The AutoMET solution (it is not a package) was created to facilitate the access and visualization of satellite imagery and products, NWP data and other meteorological information using simple functions that anyone can use and adapt, **including those not familiarized with programming**. The examples run **directly in the cloud (Google Colab)**, without the need of installing any tools (but it is also possible to adapt it and run the examples locally). Students may create images processing data available since the launch of each supported satellite! Below, some examples created with AutoMET:

![1](https://github.com/diegormsouza/automet/assets/54595784/f09c3af9-a5fc-46c4-ae96-f67364f24916)

**The Challenge:** During training events on satellite meteorology and related fields, we usually have a mixed audience (researchers, students, technicians, meteorologists, managers, etc). Hands-on programming activities are frequently demanded, but usually, most of the participants are not experienced programmers, thus taking a considerable amount of time for them to be able to produce advanced images, and some participants don't feel motivated. This solution aims to create a simple way to motivate participants to learn programming by allowing them to quickly download, process and visualize information by using **simple functions**. Then, after creating nice images, we proceed understanding how these functions work.

**Methodology:** Instead of going through the traditional learning steps (general programming aspects -> visualizing images -> motivation), this solution proposes another approach: visualizing awesome images -> motivation -> general programming concepts. This new approach has proved effective in recent training events.

**Supported Datasets (Jan 2024):**

- **Geostationary Ring (EUMETVIEW):** Global mosaics (every 3 hours) with GOES-East/West, Meteosat 0°, Meteosat 45.5° and Himawari data. Data available since June 06 2021 18:00 UTC - 'ir108', 'airmass', 'natural_color', 'ash' and 'dust' RGBs are supported.

- **GOES-East and GOES-West (AWS):** 'goes16' data available since July 10 2017, 'goes17' since August 28 2018, 'goes18' since August 02 2022. Note: please consider that goes-16 generated images every 15 minutes (instead of 10) until a few months after launch. **Note:** For the sake of speed, only ABI L2 Cloud and Moisture Imagery (Multi-Band Format) - Full Disks - 2 km resolution are supported for now. All 16 bands and more than 20 composites are supported.

- **Meteosat 0° and Meteosat 45.5° (EUMDAC):** 'msg0' tested with data since March 26 2004 (every 15 minutes). 'msg45' tested with data since February 01 2017. All 12 SEVIRI bands and more than 20 composites are supported.

- **NWP:** open ecmwf data available for download since January 21 2022 00:00 ('2022-01-21 00:00'). gfs data available for download since February 26 2021 00:00 ('2021-02-26 00:00'). gfs products: 'pgrb2.0p25', 'pgrb2.0p50', 'pgrb2.1p00'. Currently, 15 fields and their variations are supported.

- **METAR (UNIDATA):** metar data available for the last 10 days, for each hour.

- **EUMETSAT (LAND SAF and H SAF):** A variety of products from the SAFs (Satellite Application Facilities). 14 products (LEO and GEO) from the SAFs are supported.

**Links for the latest version of the Example Google Colab Notebooks (you may create a copy and adapt them according to your needs):**

- **AutoMET_01_GOES-R.ipynb:** [Link](https://colab.research.google.com/drive/1zuK7b4RmtECoNqPyiNi2Cb8t_psaQFJB?usp=sharing)
- **AutoMET_02_METEOSAT.ipynb:** [Link](https://colab.research.google.com/drive/1hWFwf_Ftz-Aod6Tr5V6hK7jKYMb8LL9t?usp=sharing)
- **AutoMET_03_SATELLITE_CASE_STUDIES.ipynb:** [Link](https://colab.research.google.com/drive/1WvX0cshlUyYFbNSmv4wKujXp5SRqmumG?usp=sharing)
- **AutoMET_04_NWP_and_METAR.ipynb:** [Link](https://colab.research.google.com/drive/1ynhgk0RAk9WxKWEv9ER1aF8GQh9iXeML?usp=sharing)
- **AutoMET_05_SATELLITE_NWP_and_METAR.ipynb:** [Link](https://colab.research.google.com/drive/1cWBawfkh-SygeXx7nZGDb4aF-8f_U6_c?usp=sharing)
- **AutoMET_06_ANIMATIONS.ipynb:** [Link](https://colab.research.google.com/drive/1TxgTEYYLxNhd1gHZfvcK-GdhvG4yjtz0?usp=sharing)
- **AutoMET_07_SAFs.ipynb:** [Link](https://colab.research.google.com/drive/1iTiWOu9mk5CePaz77JQRqyBdUkJKD2Gj?usp=sharing)

**Note:** These examples were created primarily for use during capacity building activities but they can be adapted for operations and research as well. You may adapt the functions the way you need.

Among the main packages used by AutoMET are:
- Pytroll/Satpy: https://github.com/pytroll/satpy 
- Herbie: https://github.com/blaylockbk/Herbie

**Developed by:** Diego Souza (https://github.com/diegormsouza) - INPE / CGCT / DISSM (Brazil)

**Trainees using AutoMET during a capacity building event (Uruguay - November 2023):**

![image](https://github.com/diegormsouza/automet/assets/54595784/0c3523b3-d9dc-484a-bf6b-806da5e52552)

