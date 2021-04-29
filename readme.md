# Medicare Fraud Detection
Using data from multiple government sources to detect Medicare fraud. 

![](images/banner_image.jpeg)

In the United States, Medicare is the national health insurance plan made primarily available to older citizens over the age of 65. This program is expensive, partly due to America’s aging population and sky-rocketing healthcare costs. It is financed through general government revenues (43%), payroll taxes (36%), and beneficiary premiums (15%). There are three main parts to the Medicare program:

- Medicare Part A : covers mostly inpatient hospital and hospice care.
- Medicare Part B: covers mostly hospital outpatient services, and prescriptions administered by a healthcare worker while in the hospital.
- [Medicare Part C](https://money.cnn.com/retirement/guide/insurance_health.moneymag/index16.htm): (aka - Medicare Advantage) are private plans subsidized by the government that need to offer the same coverage as Part A and Part B and are sometimes administered by private health insurance companies.

For this project, we also look into an aspect of the Medicare program, usually billed under Medicare Part B, knows as Durable Medical Equipment, Prosthetics, Orthotics and Supplies (DMEPOS).

## The Feature Data

We will be using data for Part D, Part B, DMEPOS, for our features. These datasets are released yearly by the Centers for Medicare & Medicaid Services ([CMS](https://www.cms.gov/)), and comprise specific information organized on a unique ID known as the [National Provider Identifier (NPI)](https://www.cms.gov/Regulations-and-Guidance/Administrative-Simplification/NationalProvIdentStand). This information is different for each of the three datasets, but includes features such as: submitted charges, utilization, average payments, provider gender, average submitted charges — to name a few.

This article is a high level overview of the project, so I will not get into the data processing specifics. If you are interesting in trying to replicate these results (or if you are a future reader who wants to incorporate data not available at the time of this writing) please check out the the data processing and modeling notebooks linked above. I will list the direct links to each dataset below:

- [Part D Data](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/PartD2015)
- [Part B Data](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Physician-and-Other-Supplier)
- [DMEPOS Data](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/DME)















