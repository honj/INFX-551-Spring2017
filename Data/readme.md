## Current List of Datasets
1) [Boston Community Gardens](https://data.cityofboston.gov/Health/Community-Gardens/cr3i-jj7v/data) from City of Boston
2) [Local Food Directories: Community Supported Agriculture (CSA) Directory](https://www.ams.usda.gov/local-food-directories/csas) from Agricultural Marketing Service, USDA 
3) [Food Environment Access](https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads/) from Economic Research Service, USDA
  * 9 thematic datasets
  * 2 supplemental datasets with county and state level data
4) [Local Food Directories: National Farmers Market Directory](https://www.ams.usda.gov/local-food-directories/farmersmarkets) from Agricultural Marketing Service, USDA  
5) [Garden Crop Count and Harvest Count from Washington State](https://farmingconcrete.org/mill/view.html?metric=&state=WA) from Farming Concrete
  * 2 datasets
6) [Local Food Directories: On-Farm Market Directory](https://www.ams.usda.gov/local-food-directories/onfarm) from Agricultural Marketing Service, USDA
7) [P-Patch Data](https://data.seattle.gov/browse?sortBy=relevance&sortPeriod=week&utf8=%E2%9C%93&q=p-patch) from Seattle.gov
  * 5 datasets
8) [Farmers Markets 2015](https://data.cityofchicago.org/Environment-Sustainable-Development/Farmers-Markets-2015/x5xx-pszi) from City of Chicago
9) [Urban Farms Locations](https://data.cityofchicago.org/Environment-Sustainable-Development/Urban-Farms/2a55-dhk8) from City of Chicago
## File-naming protocol
*topical coverage* **(dot)** *spatial coverage* **(dot)** *topic subset(s)* OR *NA* if not applicable **(dot)** *data source* OR *NA* if not applicable **(dot)** *date uploaded in YYYY-MM-DD* **(dot)** *file extension or ".url" if text file including url(s) of data source*
#### Controlled vocabulary
##### Topical coverage
* Community gardens = CG
* 
##### Spatial coverage
* City-level
  * City names
    * Seattle = Seattle
    * San Diego = SanDiego
    * [...]
* State-level
  * US states = State abbreviation in caps + "state"
    * Washington = WAstate
    * [...]
* National-level
  * Abbreviation in caps
    * US
    * [...]
##### Topic subsets
* Abbreviations with initial capitals, no punctuation in between
  * Example: LocOther
* Topic subset abbreviations
  * Location = Loc
  * Harvest count = Harvest
  * Crop information = Crop
  * Contact information = Contact
  * Other information = Other
##### Data sources
* As in first line of ".url" files 
* Examples:
  * Data.Seattle.Gov = DSG
  * Farming Concrete Mill = FCMill
#### File name examples
* CG.NewYorkCity.Loc.NYCOpenData.2017-06-06.csv
* CG.NewYorkCity.NA.NYCOpenData.2017-06-06.url
* CG.WAstate.CropsOther.FCMill.2017-04-11.csv
* CG.WAstate.NA.FCMill.2017-04-11.url
