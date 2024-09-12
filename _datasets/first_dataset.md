---
schema: liveme
title: Accelerometer
organization: AA BB  # read organization name from config file in the data preparation pipeline
notes: The dataset contains 3D vector of the acceleration.
resources:
    - name: codebook
    # url must link to the corresponding codebook
      url: >-
          /liveme/documentation/codebooks/accelerometer.html
      format: html
    - name: project description
      url: >-
          /liveme/documentation/shb
      format: html
    - name: Datascientia community project
      url: >-
          https://ds.datascientia.eu/community/public/projects/63cd43b5-9e20-4f36-a6b6-275946352522
      format: html
license: 'https://datascientiafoundation.github.io/LivePeople/resources/2023LivePeopleLicense.html'  # fixed field

dataset_name: Cellular Network
location: Trento (Italy)
latitude_map: 46.04  # keep fixed
longitude_map: 11.07 # keep fixed
start_date: 2020.09.28 # read from data preparation config
end_date: 2020.12.11 # read from data preparation config
dataset_type: Sensors # generated dynamically based on the current datasets
sensor_type: Connectivity # generated dynamically based on the current datasets
size: 2,56 MB  # compute based on the current datasets
dataset_format: parquet # fixed
data_origin: direct observation
number_participants: 1
language: unknown
collection_name: SHB course
project_url: https://ds.datascientia.eu/community/public/projects/63cd43b5-9e20-4f36-a6b6-275946352522
5_stars: 3 # fixed value
publication_date: 2023-11-30 00:00:00 # date of generation of the file
identifier: 004.AAAD.AAC.AM # generated based on the defined rules
request_contact: tim@timwis.com 
maintainer: Tim Wisniewski
maintainer_email: tim@timwis.com
category:
  - Personal data
type:
  - Datasets
---
