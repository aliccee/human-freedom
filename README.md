# human-freedom

Human Freedom Index


# Datasets

Our main dataset, "hfi_cc_2018.csv" comes from the 2018 Human Freedom Index report and contains 79 varaibles to cover the aspects of economic and personal freedom within 162 countries. Also from the Human Freedom Index report is a dataset "country.csv" freedom rating that is scaled 0-10 to represent the overall economic and personal freedom. Our third dataset that we have included is from the sexualviolence.org webiste, looking at conflict-related sexual violence coming from government military, pro-government militias and rebel forces. This is labled "SVAC_dataset update 2016 June 21" in our repo.

# Plan

Of the 79 varaibles there are about 10 variables realating to the freedoms of women in these respective countries. Our plan is to look at the correlations between women's freedom in countries and its overall personal and economic freedom score. We will hope to identify certain regions or anomalies where we do not find as strong of a correlation among these variables as initially expected. In regards to the SVAC dataset, we are currently unsure exactly how we want to incorporate it or if we even want to incorporate it at all into our research. Our hope is to engineer one feature relating to the prevalence of sexual violence within a country, as this seems relevant to
women's personal freedoms. But our current concerns are that the timeline is off as this cover 1989-2009 while the HFI dataset uses the year 2016. Also the data is inherently messy so we will need to do a lot of cleaning in order to make it workable.


# References

https://journals.sagepub.com/doi/abs/10.1177/0022343300037001003

http://www.sexualviolencedata.org/dataset/

https://www.cato.org/human-freedom-index-new

https://object.cato.org/sites/cato.org/files/human-freedom-index-files/human-freedom-index-2018-revised.pdf

 - Page 17: Table of variables included in personal and economic freedom
 - Page 376: Data dictionary/explanations for variables
