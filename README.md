# Examining Disaster Declarations in Search of Climate Safe Havens in the Carolinas
## OpenFEMA Datasets - Disaster Declarations

INTRODUCTION: The goal of this project is to examine the history of natural disasters in the Carolinas to help identify what areas are most & least susceptible to natural disasters and what types. I pulled all disaster declarations available and filtered my data source for just North & South Carolina, resulting in a dataset spanning 1954 to present. 

DATA/DESIGN: The data used for this project comes from the OpenFEMA Data Set from FEMA.gov. Some filtering of the data has been done, including removing any non-weather or climate disasters (namely biological and chemical), and removing certain disaster declarations for evacuation responses due to disasters in other states. I wanted to count only natural disasters such as fires, hurricanes, severe thunderstorms, and snow or ice storms. The main example of this is the Hurricane Katrina Evacuation Response. Since this disaster declaration in the Carolinas was for an evacuation response for a disaster in a different state, I removed it. Additionally, a few calculated fields were created to ensure counties could be mapped & displayed properly, and that declarations for Hurricane Helene were accurately counted.

FUTURE WORK: I would like to smooth out the general functionality of the dashboard as a whole, while also combining the FEMA data with data from the National Weather Service. Some of the incident categories or labels seem to lack consistency between events, so I believe joining NWS or NOAA data sources would clean that up. It would also allow me to overlay additional details lacking in the FEMA data sets, such as max wind speeds, rainfall, snow totals, etc. Additional FEMA or other disaster data resources that include damage totals, casualties, and power losses would be great context for each disaster event. 

View my Tableau Dashboard at this Link: [https://public.tableau.com/views/WherearetheClimateSafeHavensintheCarolinas_BennettS/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]

Data Source Link: [https://www.fema.gov/openfema-data-page/disaster-declarations-summaries-v2]
