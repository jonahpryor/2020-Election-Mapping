# 2020-Election-Mapping
This project maps the results of the 2020 U.S. presidential election using FIPS, which are unique geographic identifiers used for identifying counties and/or states. The project builds a function that plots the results of the 2020 election using up to three arguments:

  - _electoral_ (T or F)
  - _vote_type_ ("absentee", "in-person", or "total")
  - _region_ (see https://cran.r-project.org/web/packages/usmap/usmap.pdf for list of available regions)

This project requires the following R packages: _tidyverse, lubridate, usmap, gridExtra_

Election data is from November 15, 2020, and is courtesy of the New York Times. Sample maps can be found in the _.pdf_ file.

NOTE: This project does not account for the split electoral votes in Maine and Nebraska. This project awards all four Maine votes to Joe Biden, and all five Nebraska votes to Donald Trump. However, this does not impact the total number electoral votes for either candidate, as Biden won one vote in Nebraska and Trump won one vote in Maine.
