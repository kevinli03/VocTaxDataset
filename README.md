# Varieties of Capitalism and Tax Dataset
Created for: 6SSPP330 Economic Policy-Making (King's College London, 2023-2024 Fall Term)
Candidate Number: AE05750

## Overview
This is a dataset consisting of OECD countries that are Liberal or Coordinated Market Econmies. It consists of their Variety of Capitalism (Liberal Market Economy or Coordinated Market Economy), a few measurements of tax policy, and several relevant control variables. The data is from 2004-2020.
In this repository, you will find:
* The Dataset (In EXCEL, CSV, and STATA form). See 'dataset' folder.
* List of sources of the data (see below).
* Data requested from OECD, KOF (In EXCEL format). See 'datasources' folder
* Codebook describing the Variables (see below).

## Codebook and Variables
The dataset is a time-series data with country-time observations from 2004-2020. There are no missing observations in any variable. All variables have an observation for every country-time combination.

### id
The ID of the observation. Each country-time observation gets its own unique ID

### countryid
The ID of the country. Each country in the dataset is assigned an ID. Does not follow international Country ID standards. To use with other data, use the 'countrycode' variable. I may update this eventually to QoG standards.

### countrycode
The country code of each country. Each country in the dataset is assigned a country code. Follows ISO 3166-1 alpha-3 Three letter code standards.

### year
The year of the observation. Ranges between 2004 to 2020.

### voc
The variety of capitalism of a particular country. Binary variable, with 0 coding liberal market economies, and 1 coding coordinated market economies. Classification is based on Witt et al (2018). <sup>1</sup>

### taxpercent
The tax revenue as % of GDP of a country in a given year. Obtained from OECD. <sup>2</sup>

### corporatetax
The combined corporate tax rate percentage of a country in a given year, combining all levels of government. Obtained from OECD. <sup>2</sup>

### personaltax
The net personal marginal tax rate: principal earner (% gross wage earnings) of a country in a given year. The “tax” here includes personal income tax, social security, and payroll taxes, and excludes wealth taxes and consumption taxes. <sup>3</sup>

### econglobal
The economic globalisation indictor from the KOF Index of Globalisation.<sup>4</sup> This is calculated through a combination of trade and financial globalisation. <sup>5</sup>

### gini
The income gini coefficient of a country in a given year. Obtained from OECD. <sup>2</sup>

### socialexp
The social expenditure as % of GDP of a country in a given year. Obtained from OECD. <sup>2</sup>

### export
The exports as % of GDP of a country in a given year. Obtained from OECD. <sup>2</sup>

## References

