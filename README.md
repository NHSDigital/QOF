> Warning: This is the README for the publically accessible version of the QOF package. If you are an internal analyst please don't use the below instructions to run the publication process.

<p>&nbsp;</p>

# QOF

## Contact Information

Repository owner: Primary Care Domain Analytical Team

Email: primarycare.domain@nhs.net

To contact us raise an issue on Github or via email and we will respond promptly.

<p>&nbsp;</p>

## Publication Summary

The objective of the Quality and Outcomes Framework (QOF) is to improve the care patients are given by rewarding practices for the quality of care they provide to their patients, based on several indicators across a range of key areas of clinical care and public health. This publication provides data for the reporting year 1 April 2022 to 31 March 2023 and covers all General Practices in England that participated in QOF in 2022-23.

Due to the impact of the COVID-19 pandemic on activity in general practice, payment protection was applied to the 2021-22 QOF service and may affect QOF activity and/or its recording for that year. Practices were advised in March 2022 that temporary income protection arrangements would not be applied to the 2022-23 QOF service. Consequently, indicator groups that contain indicators to which payment protection was applied in 2021-22 have not been compared to 2022-23 achievement data.

More information on payment protection can be found in the ‘Technical Annex’ which forms part of this publication and the 'Letters to practices' found under 'Related Links' below.

GP practices have been mapped to their respective PCNs, Sub ICB Locations, ICBs and Regions using reference data current on 1 April 2023. This mapping has been applied to data for both the current and previous reporting year.

The publications can be found here:

https://digital.nhs.uk/data-and-information/publications/statistical/quality-and-outcomes-framework-achievement-prevalence-and-exceptions-data

<p>&nbsp;</p>

## Set up
1. Make a [clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) of the repository on your local machine.
2. Update config.json accordingly.
3. Run QOF_22_23_v2.ipynb.

<p>&nbsp;</p>

## Creating a file structure 
```
root
|
|---LIVE
|   |
|   |---PROCESS 1
|   |   |
|   |   |---INPUTS
|   |   |   |
|   |   |   |---Templates
|   |   |
|   |   |---OUTPUTS
|   |   |   |
|   |   |   |---DO NOT PUBLISH
|
|---CHECKING
```
<p>&nbsp;</p>

## Instructions for publication production
Read the guidance https://nhsd-confluence.digital.nhs.uk/display/KH/Quality+and+Outcomes+Framework+%28QOF%29+data+download+and+publication+guidance.

## QOF Acronym dictonary
- ach	= achievement
- adj	= adjusted
- cols = columns
- dedup = deduplicate (i.e. duplicates removed)
- dup	= duplicate
- denom = denominator
- dom = domain
- geog = geography or geographies
- gr = group
- ind = indicator
- list = list
- max = maximum
- min = minimum
- num = numerator
- org = organisation
- ov = over
- piv = pivot
- prac = practice
- ref = reference
- reg = register
- subdom = sub domain
- sup = suppressed
- un = under


## Licence
QOF codebase is released under the MIT License.

The documentation is © Crown copyright and available under the terms of the Open Government 3.0 licence.
