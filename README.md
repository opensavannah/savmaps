![SavMaps logo](https://cvlassets.s3.amazonaws.com/savmaps.png)
# SavMaps.io

SavMaps is the working title for a interactive map of resources available to those residing in Savannah. Started Aug. 9th, 2017, at [Open Savannah](http://opensavannah.org)'s [Community Idea Launchpad](https://www.meetup.com/OpenSavannah/events/241867891/), the SavMaps project is in its development phase, timeline to be determined. It utilizes [Leaflet](https://github.com/Leaflet/Leaflet), [Tabletop.js](https://github.com/jsoma/tabletop), and [Google Sheets](https://www.google.com/sheets/about/).

---
## About the project

### Why SavMaps?
Data on local social service programs and community resources can often be hard to locate – especially for those in need of aid and their case workers. While literally hundreds of different organizations offer community programs and public services in the Coastal Georgia region, the sheer number of program providers makes it hard to keep track of, much less keep that data updated in a single place for purposes of analysis and planning.

### What will we be doing for SavMaps?
We'll be partnering with [Coastal Georgia Indicators Coalition](http://www.coastalgaindicators.org/) to build an interactive mapping web app that allows users to locate the nearest resources to their current location, filter the map by types of resources, and even overlay Census Data to find possible trends in the geographic distribution of aid organizations. Following on the heels of SavBook.io –– a handy mobile web app we built in March in a single evening that will soon be featured on Chatham County's website. We'll also be using the data we entered for SavBook as a starting point to turn street addresses into latitude-longitude coordinates for plotting on the maps.

### What skills do I need to contribute?

*All that one needs to be able to do is to enter data into a spreadsheet to contribute to the project in a meaningful and impactful way.*

The full project will also require a mix of designers, data people, GIS types, a couple of JavaScript developers, and plenty of creative problem-solvers. Most importantly, we'll need community members with locality knowledge from across the area to make the project a success. All contributors will be credited for their work by having their names listed on the landing page for the web app.

## Repository Notes

The repository that houses all of the resource information is a Google Sheet to allow easy entry of new resources. At minimum, a resource's name, its category, and its address is needed.

Information gathered there will be ported over to the SavMaps on a rolling basis by the project maintainer. They will verify the accuracy of the resource, provide a latitude/logitude and fill in any missing information.

[This Google workbook that populates the map can be freely edited](https://docs.google.com/spreadsheets/d/15TEKVg5rdZM6ih8GpVe9vDlwO-kwMpEUtZPL7u_rcDw/edit#gid=27956486)


## Categories
*Suggest additional categories through opening an [issue](https://github.com/opensavannah/savmaps/issues).*

This project uses the [openeligibility](https://about.auntbertha.com/openeligibility) taxonomy to define the categories that are applied to each of the resources. It is compatable with the [Human Services Data Specification](https://github.com/openreferral/specification), [HSDS v1.1 readthedocs](https://openreferral.readthedocs.io/en/latest/), and Code for America's [Ohana projects](https://github.com/search?q=org%3Acodeforamerica+ohana). 

SavMaps extends __openeligibility__ by including two additional categories: __cultural__ and __civic__.

### Color coding

- Money: green
- Housing: lightgreen
- Goods: blue
- Transit: orange
- Health: purple
- Care: lightblue
- Euducation: lightred
- Work: darkpurple
- Legal: gray
- Cultural: cadetblue
- Food: darkgreen
- Civic: darkblue

[View old spreadsheet](https://docs.google.com/spreadsheets/d/1_Ep9pCtsdoIiavyGkzPNJ4Vb7JwsU744l8Yax1_Az9k/edit?usp=sharing). 
[View SavBook data for reference](https://docs.google.com/spreadsheets/d/1_Ep9pCtsdoIiavyGkzPNJ4Vb7JwsU744l8Yax1_Az9k/edit?usp=sharing).

