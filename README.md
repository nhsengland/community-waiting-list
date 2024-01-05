# Community Waiting List Regional Analysis
## NHS South West Intelligence and Insights Team

### About the Project

This is an analysis of community waiting times, it can be run across national data and drawne down to a regional level.

_**Note:** Only public or fake data are shared in this repository._

### Project Stucture

- The main code is found in the root of the repository (see Usage below for more information)

### Built With

[R Studio](RStudio Team (2020). RStudio: Integrated Development for R. RStudio, PBC, Boston, MA URL http://www.rstudio.com/.)  
[R Statistical Software](  R Core Team (2018). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. URL https://www.R-project.org/.)

- library(tidyverse)
- library(janitor)
- library(readxl)
- library(NHSRplotthedots)
- library(gt)
- library(gtExtras)
- library(english)

### Getting Started

#### Installation

To get a local copy up and running follow these simple steps.

Clone the repo

### Usage
Data is drawn from NHSE Udal data warehouse.

Similar data data for this code is can ve obtained obtain from NHS futures, unfortunately it is in a differrnt format.

https://future.nhs.uk/CommunityHealthServices/view?objectId=16189616

The report runs for NHS England region to show regional and local ICB comparisons.

You can select the region that the report runs against at the start of the code. 

#### Outputs
The report produces an interactive quarto document that is published here https://future.nhs.uk/SouthWestAnalytics .

#### Datasets
Data from this code is taken from UDAL NHSE Data warehouse.  If you have access you will need to run report in UDAL enviorment.

You will need to set up a source file with your personal details, with your 


Data for this code is currently obtain from NHS futures.

https://future.nhs.uk/CommunityHealthServices/view?objectId=16189616

This data is made available publicaly, just not in this format.

Future version will draw data directly from UDAL.

### Roadmap

See the {LINK TO REPO ISSUES} for a list of proposed features (and known issues).

### Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

_See [CONTRIBUTING.md](./CONTRIBUTING.md) for detailed guidance._

### License

Unless stated otherwise, the codebase is released under [the MIT Licence][mit].
This covers both the codebase and any sample code in the documentation.

_See [LICENSE](./LICENSE) for more information._

The documentation is [© Crown copyright][copyright] and available under the terms
of the [Open Government 3.0][ogl] licence.

[mit]: LICENCE
[copyright]: http://www.nationalarchives.gov.uk/information-management/re-using-public-sector-information/uk-government-licensing-framework/crown-copyright/
[ogl]: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/

### Contact

Simon Wellesley-Miller

To find out more  get in touch at [Simon.Wellesley-Miller](mailto:simon.wellesley-miller@nhs.net).



