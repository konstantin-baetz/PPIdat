# Codebook

## Indicator variables

Each row represents one country-year. 

This dataset covers two years, 2017 and 2019, which is denoted in the variable *year*.

Countries are indicated by the variables *country*, which give the long form name of the country, as well as the *ccode* and *stateabb* variables which can be used for merging. *ccode* is the numeric country cowcode and *stateabb* is the ISO 3166-1 alpha-3 country code.

## Substantial variables

The PPI is calculated as the sum of five subindices:

| Variable 	| Description 	|
|:---:	|:---:	|
| *intl_commitment* 	| International Commitment to preventing strategic commodity trafficking 	|
| *legislation* 	| Legislation in place that regulates and oversees trade in strategic commodities, and criminalizes and aims to prevent strategic commodity trafficking 	|
| *ability_trade* 	| Ability to Monitor and Detect Strategic Trade 	|
| *ability_financing* 	| Ability to Prevent Proliferation Financing 	|
| *enforcement* 	| Adequacy of Enforcement against strategic commodity trafficking 	|

The sum of these is given in the full PPI and the variable *points*.

For more information on how these variables are constructed, see /source/ in this repo.
