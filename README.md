Last Revised: 01/05/2026

Point of Contact: Abigayle Hodson, Scientific Engineering Associate, Abigayle_Hodson@lbl.gov

Principle Investigator: Dr. Jennifer Stokes-Draut, Energy/Environmental Policy Research Scientist/Engineer

Organization: Lawrence Berkeley National Lab

Purpose: The purpose of this notebook is to assess the accuracy of different methods for estimating wastewater treatment plant energy consumption and recovery. Methods for estimating electricity consumption, energy consumption, and electricity generation from biogas utilization are applied herein to an inventory of U.S. wastewater treatment plants derived from the U.S. EPA's Clean Watersheds Needs Survey (CWNS). Using reported energy consumption/recovery values for select U.S. cities published in the 2018 study "[The State of U.S. Urban Water: Data and the Energy-Water Nexus,](https://agupubs.onlinelibrary.wiley.com/doi/epdf/10.1002/2017WR022265)" the error associated with each of the estimation methods is calculated and visualized using kernel density estimation (KDE) plots. Error is also evaluated based on facility characteristics such as size, effluent treatment level (ETL), and latitude.

Data Sources:
*   Clean Watersheds Needs Survey (CWNS) (U.S. EPA, [2004](https://www.epa.gov/cwns/clean-watersheds-needs-survey-cwns-2004-report-and-data), [2008](https://ordspub.epa.gov/ords/cwns2008/f?p=cwns2008:25:), [2012](https://ordspub.epa.gov/ords/cwns2012/f?p=cwns2012:25:), and [2022](https://sdwis.epa.gov/ords/sfdw_pub/r/sfdw/cwns_pub/data-download?session=9748529459785))
*   Department of Energy Combined Heat and Power Database
([U.S. DOE, 2024](https://doe.icfwebservices.com/downloads/chp))
*   U.S. Energy Information Administration Survey Form EIA-923, 2012
([U.S. EIA, 2012](https://www.eia.gov/electricity/data/eia923/))
*   Water Environment Federation Biogas Database ([WEF, 2024](https://app.powerbi.com/view?r=eyJrIjoiMGFjZDFjZmItMjQ5Yi00ZTlhLWJmNTQtODFiNjlkYjFlODJjIiwidCI6ImI3ZTk3ODAyLTJhNjktNDc3ZS1iN2QyLWY0ZDE2MWMyMTBjYiIsImMiOjF9))
*   Electric Power Research Institute (EPRI) Electricity Intensity Based on Flow Rate, ETL, and Key Unit Processes ([Pabi et. al, 2013](https://www.sciencetheearth.com/uploads/2/4/6/5/24658156/electricity_use_and_management_in_the_municipal_water_supply_and_wastewater_industries.pdf))
*   Electricity Intensity Based on ETL ([Li et al., 2025](https://pubs.acs.org/doi/10.1021/acs.estlett.4c00893))
*   Electricity/Energy Intensity Based on Treatment Configuration, Original ([Tarallo et. al, 2015](https://iwaponline.com/ebooks/book/293/A-Guide-to-Net-Zero-Energy-Solutions-for-Water))
*   Electricity/Energy Intensity Based on Treatment Configuration, Updated ( [El Abbadi et al., 2025](https://www.nature.com/articles/s44221-025-00485-w))
*   Electricity Intensity Based on Key Unit Processes ([Plappally and Leinhard, 2012](https://www.sciencedirect.com/science/article/pii/S1364032112003541))
*   Electricity Generation Intensity Based on Prime Mover ([EPA, 2011](https://www.epa.gov/sites/default/files/2015-07/documents/opportunities_for_combined_heat_and_power_at_wastewater_treatment_facilities_market_analysis_and_lessons_from_the_field.pdf))
*   Regression Model of Energy Use ([Carlson and Walburger, 2007](https://www.nyserda.ny.gov/-/media/Project/Nyserda/Files/EERP/Commercial/Sector/Municipal-Water-Wastewater-Facilities/benchmarking-water-wastewater-utilities.pdf))
