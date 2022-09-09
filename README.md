# UFOs

## Overview

The purpose of this analysis is to display information about UFO sightings on a web page. This information includes categories for date, city, state, country, shape, duration and comments. Additionally, search filters are added which allow users to filter results by date, city, state, country, and shape.

## Results

In order to perform a search, all that is necesary is to enter search criteria into the desired category and then press enter.

An example of filtering the table by the cities column can be found below:

<img width="947" alt="filter_cities" src="https://user-images.githubusercontent.com/107224097/189417987-9556c937-6615-45ab-b841-3b5d51b452c8.PNG">

An example of filtering the table by the shape column can be found below:

<img width="942" alt="filter_light" src="https://user-images.githubusercontent.com/107224097/189418194-43a6b090-2895-4876-87ba-708353e96d77.PNG">

The top portion of the home page:

<img width="946" alt="home" src="https://user-images.githubusercontent.com/107224097/189418306-9d1f0b04-d34b-473f-8eef-6636a25be6d1.PNG">

## Summary

One drawback of this design is that with a large data set, some searches can result in a very long table. For example, filtering results for only the country of the US results in a long page. An improvement could be to split results into additional pages for results over a certain length. 

## Resources

The original information used in the table can be found under the static and js folders, titled data.js. The D3 library is used to produce the dynamic web elements. CSS sheet is used to style the look of HTML.
