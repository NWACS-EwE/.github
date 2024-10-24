# NWACS-MICE
## Objective 1: Model Development
### Ecopath Updates and Inputs
#### Species Included
No new species or age stanzas were added to the MICE model for this update.  Some considerations was given to adding osprey, bluefin tuna, white hake, blue catfish, mammals, HMS, birds, squid, crabs, lobster, river herring, eel, and smooth dogfish.  Ultimately the ERP WG elected to maintain the current species and age structure of the MICE model, and will consider parsing out some species in the NWACS-FULL model.
#### Update Inputs from Stock Assessments
R-scripts were developed to process stock assessment output files to extract data and generate inputs for NWACS-MICE.  Because the intention is to develop Ecospace models, all biomass and landings inputs were converted from 1,000 mt to mt/km2 in the current model.  Assessments for Striped bass and weakfish are currently ongoing and will be updated when available.  Jainita is working on processing the non-ERP species.
| Species           | Assess Year | Terminal Year | Status  | Comments                                                                    |
|-------------------|-------------|---------------|---------|-----------------------------------------------------------------------------|
| Atlantic herring  | 2024        | 2023          | ü       |                                                                             |
| Atlantic menhaden | 2022        | 2021          | ü       | BAM mid-year biomass                                                        |
| Bluefish          | 2023        | 2022          | ü       | calculated Bbar; subtracted juv Z by 1; need to double check rep processing |
| Striped bass      | 2022        | 2021          | ü       | Calculated Bbar; need to check rep file, no FAA; stanza 2 leading           |
| Striped bass      | 2024        | 2023          | NA      |                                                                             |
| Spiny dogfish     | 2023        | 2022          | ü       | SS3 mid year biomass                                                        |
| Weakfish          | 2019        | 2017          | ü       | Calculated Bbar; low juv Z                                                  |
| Weakfish          | 2024        | 2023          | NA      |                                                                             |
