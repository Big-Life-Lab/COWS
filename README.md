# Canadian Open Wastewater Surveillance Database

## Description

The repository is used to store Canadian wastewater data using the Ottawa Data Model ([ODM](https://github.com/Big-Life-Lab/ODM)).

## Background

Wastewater testing and surveillance (WWS) has a long history as a public health tool, helping us monitor polio outbreaks and track antimicrobial resistance. With the COVID-19 pandemic and the emergence of the SARS-CoV-2 virus, a new opportunity has emerged to leverage WWS to inform prevention and control of the pandemic. People infected with the SARS-CoV-2 virus shed the virus in their stool, meaning that the feces in wastewater systems can be checked to detect outbreaks and monitor for variants even before people become symptomatic. With over 200 wastewater testing sites across Canada, and over 2000 testing sites in over 50 countries, WWS has proven itself to be an effective tool in the fight against the virus. However, despite the rapid growth in this field and the swift deployment of WWS programs nationally, there is very little data sharing due to the absence of a centralized data repository with controlled vocabulary. This absence has led to varied data and assay quality, inconsistent reporting of wastewater test results, little adjustment of wastewater results, and has slowed the development of wastewater-based epidemiology.

That is why we developed the Canadian Open Wastewater Surveillance (COWS) Database. This centralized database, funded by CoVaRR Net, the Canadian Institute for Health network, serves as an central depository for open access wastewater surveillance data. This will shrink the delay between the measurement and analysis, and provide more data for better modeling, better collaboration, and better tools in the fight against the COVID-19 pandemic.

To ensure that the COWS database is usable for all users, we use the Open Data Model ([ODM](https://github.com/Big-Life-Lab/ODM)). The ODM an open, standard approach to share wastewater surveillance data. The ODM helps the wastewater surveillance community collaborate by allowing teams worldwide to share their data in a common structure. The model uses a relational dictionary to map more than 150 variables into 10 tables, and offers documentation on how to use the model, template files to record data in the ODM format, and scripts of code to set up a relational database according to the ODM schema.

## Current Objectives

- **Create the most robust open data model for wastewater and environmental epidemiology and surveillance.** Supported by an international steering committee, the ODM dictionary will allow consistent reporting of SARS-CoV-2, including variants and mutations. The ODM will support reporting for other health hazards, including other microbes and chemicals. Reporting will expand beyond wastewater to include other environmental testing such as air and surfaces.

- **Release the automated data validation and transformation tools.** This will automate data validation using the Open Data Model validation schema and rule set. This will speed up data processing for use in modeling, and provide support to labs and other data custodians to make sure the data they share data the standardized Open Data Model format.

- **Start data storage, and manage access.** This database will use the Open Data Model to allow wastewater testing labs to share their using an open access, open science approach. Public health practitioners, epidemiologists and others access the database to download data for their use. The priorities for this database are for widely accessible, open data that follows the FAIR data principles for findability, accessibility, interoperability, and reusability.
