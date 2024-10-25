# Examining Disaster Declarations in Search of Climate Havens in the Carolinas
## OpenFEMA Datasets - Disaster Declarations

INTRODUCTION: This goal of this project is to examine the history of natural disasters in the Carolinas (North & South Carolina) to help identify what areas are most susceptiple to natural disasters and what types.

DATA/DESIGN: The data used for this project comes from the OpenFEMA Data Set from FEMA.gov. Some filtering of the data has been done, including removing any non-natural disasters (namely biological and chemical), and also removing certain disaster declarations that were for evacuation responses. The main example of this is the Hurricane Katrina Evacuation Response. Since this disaster declaration in the Carolinas was for evacuation responses, and not an in-state natural disaster event, I removed it. Additionally, a few calculated fields were created to ensure counties could be mapped properly and that declarations for Hurricane Helene were accurately counted. 

FUTURE WORK: I would like to smooth out the general functionality of the project as a whole, while also combining the FEMA data wiith data from the National Weather Service. Some of the incident types seem to lack consistency between events, so I believe combining data with the NWS or NOAA data sources would clean that up, while also allowing me to overlay additional details lacking in the FEMA data sets. 

View my Tableau Dashboard at this Link: [https://public.tableau.com/views/WherearetheClimateSafeHavensintheCarolinas_BennettS/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]
