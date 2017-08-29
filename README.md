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

This project uses the [openeligibility](https://about.auntbertha.com/openeligibility) taxonomy to define the categories that are applied to each of the resources. It is compatable with the [Human Services Data Specification](https://github.com/openreferral/specification) (HSDS) and Code for America's [Ohana projects](https://github.com/search?q=org%3Acodeforamerica+ohana). 

SavMaps extends __openeligibility__ by including two additional categories: __cultural__ and __civic__.

### Color coding

|Color Name|Color|Hex|RGB|Resource|
|-----|----------|---|---|--------|
| Red | ![#f03c15](https://placehold.it/100x25/e6194b/000000?text=+) | #e6194b | (230, 25, 75) | Emergency |
| Green | ![#3cb44b](https://placehold.it/100x25/3cb44b/000000?text=+) | #3cb44b | (60, 180, 75) | Money |
| Yellow | ![#ffe119](https://placehold.it/100x25/ffe119/000000?text=+) | #ffe119 | (255, 225, 25) | Housing |
| Blue | ![#0082c8](https://placehold.it/100x25/0082c8/000000?text=+) | #0082c8 | (0, 130, 200) | Goods |
| Orange | ![#f58231](https://placehold.it/100x25/f58231/000000?text=+) | #f58231 | (245, 130, 48) | Transit |
| Purple | ![#911eb4](https://placehold.it/100x25/911eb4/000000?text=+) | #911eb4 | (145, 30, 180) | Health |
| Cyan | ![#46f0f0](https://placehold.it/100x25/46f0f0/000000?text=+) | #46f0f0 | (70, 240, 240) | Care |
| Magenta | ![#f032e6](https://placehold.it/100x25/f032e6/000000?text=+) | #f032e6 | (240, 50, 230) | Education |
| Lime | ![#d2f53c](https://placehold.it/100x25/d2f53c/000000?text=+) | #d2f53c | (210, 245, 60) | Unused |
| Pink | ![#fabebe](https://placehold.it/100x25/fabebe/000000?text=+) | #fabebe | (250, 190, 190) | Unused |
| Teal | ![#008080](https://placehold.it/100x25/008080/000000?text=+) | #008080 | (0, 128, 128) | Work |
| Lavender | ![#e6beff](https://placehold.it/100x25/e6beff/000000?text=+) | #e6beff | (230, 190, 255) | Unused |
| Brown | ![#aa6e28](https://placehold.it/100x25/aa6e28/000000?text=+) | #aa6e28 | (170, 110, 40) | Legal |
| Beige | ![#fffac8](https://placehold.it/100x25/fffac8/000000?text=+) | #fffac8 | (255, 250, 200) | Unused |
| Maroon | ![#800000](https://placehold.it/100x25/800000/000000?text=+) | #800000 | (128, 0, 0) | Cultural |
| Mint | ![#aaffc3](https://placehold.it/100x25/aaffc3/000000?text=+) | #aaffc3 | (170, 255, 195) | Unused |
| Olive | ![#808000](https://placehold.it/100x25/808000/000000?text=+) | #808000 | (128, 128, 0) | Food |
| Coral | ![#ffd8b1](https://placehold.it/100x25/ffd8b1/000000?text=+) | #ffd8b1 | (255, 215, 180) | Unused |
| Navy | ![#000080](https://placehold.it/100x25/000080/000000?text=+) | #000080 | (0, 0, 128) | Civic |
| Grey | ![#808080](https://placehold.it/100x25/808080/000000?text=+) | #808080 | (128, 128, 128) | Unused |
| White | ![#FFFFFF](https://placehold.it/100x25/FFFFFF/000000?text=+) | #FFFFFF | (255, 255, 255) | Reserved for icon color |
| Black | ![#000000](https://placehold.it/100x25/000000/000000?text=+) | #000000 | (0, 0, 0) | Reserved for icon color |

_based off of Sasha Trubetskoy's [list of distinct colors](https://sashat.me/2017/01/11/list-of-20-simple-distinct-colors/)._

---

[View old spreadsheet](https://docs.google.com/spreadsheets/d/1_Ep9pCtsdoIiavyGkzPNJ4Vb7JwsU744l8Yax1_Az9k/edit?usp=sharing). 
[View SavBook data for reference](https://docs.google.com/spreadsheets/d/1_Ep9pCtsdoIiavyGkzPNJ4Vb7JwsU744l8Yax1_Az9k/edit?usp=sharing).

