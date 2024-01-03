> Warning: This is the README for the publically accessible version of the QOF package. If you are an internal analyst please don't use the below instructions to run the publication process.

<p>&nbsp;</p>

# QOF

## Contact Information

Repository owner: Primary Care Domain Analytical Team

Email: primarycare.domain@nhs.net

To contact us raise an issue on Github or via email and we will respond promptly.

<p>&nbsp;</p>

## Publication Summary

The objective of the Quality and Outcomes Framework (QOF) is to improve the care patients are given by rewarding practices for the quality of care they provide to their patients, based on several indicators across a range of key areas of clinical care and public health. The publication provides data for the reporting year 1 April 2022 to 31 March 2023 and covers all General Practices in England that participated in QOF in 2022-23.

The publications can be found here:

https://digital.nhs.uk/data-and-information/publications/statistical/quality-and-outcomes-framework-achievement-prevalence-and-exceptions-data

<p>&nbsp;</p>

## Repository Summary

> Whilst this repository is the publically accessible version, the main aim of this repository is to inform users how the publication outputs and indicators within the publication were produced and is unlikely to benefit users with regards to running and producing the publication outputs due to the specific nature of the input data required.

Please note that you may not be able to run the code as this requires access to a private SQL server. The data on the private server contains reference data that is used for mapping and patient registration purposes. The reference tables used contain data from the epraccur file which can be downloaded from this [webpage](https://digital.nhs.uk/services/organisation-data-service/file-downloads/gp-and-gp-practice-related-data), and a restricted patient registration report from the National Health Applications and Infrastructure Service (NHAIS); the NHAIS patient registration data is however published each month [here](https://digital.nhs.uk/data-and-information/publications/statistical/patients-registered-at-a-gp-practice).

<p>&nbsp;</p>

## Set up

1. Make a [clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) of the repository on your local machine.
2. Update config.json accordingly.
3. Run QOF_22_23_v2.ipynb.
> If you are running for publication you will need to amend the code so that test_run = False is unhashed

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
> Please note that for test runs all outputs will be located within the test folder which is automatically created in your working directory

<p>&nbsp;</p>

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
