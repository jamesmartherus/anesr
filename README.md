# `anesr`: Easy access to ANES data in R <img src="man/figures/logo.png" align="right" width=120 />

The American National Election Studies are one of the most important sources of data for political scientists. `anesr` provides easy access to ANES data for R users. `anesr` includes tidy versions of all ANES pilot and time series studies as compact, rda objects. Once the package is installed and loaded, any dataset can be accessed using the `data()` function. `anesr` also includes documentation for some studies in tidy format. Documentation files include descriptions, coding, and marginals or summary statistics for all variables in the dataset. 

## Installation

To install `anesr`, use the `install_github` function from the `devtools` package:

```
library(devtools)
install_github("jamesmartherus/anesr")
```


### Examples

```
library(anesr)

data(package="anesr") #View a list of available datasets

data(timeseries_cum) #Load Time Series Cumulative File (1948-2016)
data(timeseries_cum_doc) #Load documentation for the Time Series Cumulative File

data(pilot_2018) #Load 2018 Pilot Study
```

# Terms of Use

By using these data, you agree to the terms of use established by the ANES:

- Use these datasets solely for research or statistical purposes and not for investigation of specific survey respondents.
- Make no use of the identity of any survey respondent(s) discovered intentionally or inadvertently, and to advise ANES of any such discovery (anes@electionstudies.org)
- Cite ANES data and documentation in your work that makes use of the data and documentation. Authors of publications based on ANES data should send citations of their published works to ANES for inclusion in our bibliography of related publications.
- You acknowledge that the original collector of the data, ANES, and the relevant funding agency/agencies bear no responsibility for use of the data or for interpretations or inferences based upon such uses.

ANES is not responsible for any errors in these datasets - any mistakes are mine. 

# Acknowledgments

- The [ANES](https://electionstudies.org/) is administered through a collaboration between [Stanford University](https://www.stanford.edu/) and the [University of Michigan](https://umich.edu/) with funding by the [National Science Foundation](https://www.nsf.gov). 
- `anesr` is inspired by [Kieran Healy's](https://kieranhealy.org/) excellent `gssr` [package](https://github.com/kjhealy/gssr). I used Kieran's [SDA parser](https://github.com/kjhealy/sda_parser) to generate documentation files. You should follow Kieran on [Twitter](https://twitter.com/kjhealy). 




