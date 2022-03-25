
# Vaccine Equity Dashboard Data
---

The availability of multidimensional, high-quality data is critical to supporting governments in making well-informed, data-driven decisions during the ongoing COVID-19 pandemic. For a better, more equitable recovery, effective COVID-19 vaccines need to be distributed widely and fairly, accounting for global and subnational vulnerabilities and leaving no one behind. Thus, global supply, allocation, utilization capabilities and cost of vaccines are all crucial to assessing the equitability of COVID-19 vaccination efforts.

The Global Dashboard for Vaccine Equity is a joint initiative of UNDP, WHO and the University of Oxford with cooperation across the UN system, anchored in the SDG 3 Global Action Plan for Healthy Lives and Well-being for All. It’s a global advocacy platform that makes an evidence-based case for additional global effort and country support on vaccine distribution and support.

It draws available information from existing COVID-19 dashboards and datasets. It combines these with socio-economic information, to position the goal of Vaccine Equity in the broader context of development challenges.</p>

The multidimensional and socio-economic approach to vaccine equity provides new insights into access to and affordability of vaccines globally anchored in fundamental development challenges of debt, economic recovery, employment, and welfare.

## Our Dataset
Currently, the country and regionallevel data presented on the Global Dashboard is divided into three broad themes.

### Accessibility:
includes variables that describe the current global supply and its utilisation and in-country prioritisation.	

| Variable      | Variable Name | Variable Description  | Source |
| ------------- |-------------| -----| -----|
| <code>securedvaccineofpopulation</code>     | Secured and/or Expected Vaccine Supply in total doses (% of population) | Final total secured and/or expected vaccine supply including bilateral deals, bilateral donations, COVAX, domestic supply and others (doses as percent of population). | [IMF-WHO-COVID-19-Vaccine-Supply-Tracker](https://www.imf.org/en/Topics/imf-and-covid19/IMF-WHO-COVID-19-Vaccine-Supply-Tracker)
| <code>deliveredpopulation</code>      | Vaccine doses received (% of population)| Delivered vaccines includes vaccines that have been made available in the country (% of population)| [Multilateral Leaders Task Force on COVID-19](https://data.covid19taskforce.com/data/tools/vaccine-delivery) |
| <code>donationsoftotal</code>     | Percent donations received | Records the number of received vaccine donations as a percentage of all vaccine deliveries.| [IMF-WHO-COVID-19-Vaccine-Supply-Tracker](https://www.imf.org/en/Topics/imf-and-covid19/IMF-WHO-COVID-19-Vaccine-Supply-Tracker) |
| <code>utilrate_lag</code>     | Percentage administered of total delivered vaccines | Percentage of the delivered vaccines that have been administered. A two-week lag is used for delivered vaccines to allow for delivery lead time.| [Multilateral Leaders Task Force on COVID-19](https://data.covid19taskforce.com/data/tools/vaccine-delivery) |
| <code>vaccine_willingness_monthly</code>     | Vaccine willingness | Percentage of individuals who would get vaccinated once a vaccine is available and recommended. |[Risk Communication Community Engagement (RCCE)](https://www.rcce-collective.net/data/behavioural-indicators/) |
| <code>h7_vaccinationpolicy</code>     | Vaccination delivery policy | Records policies for vaccine delivery for different groups: <br> 0 - No availability <br>1 - Availability for ONE of following: key workers/ clinically vulnerable groups (non elderly) / elderly groups <br> 2 - Availability for TWO of following: key workers/ clinically vulnerable groups (non elderly) / elderly groups <br> 3 - Availability for ALL of following: key workers/ clinically vulnerable groups (non elderly) / elderly groups<br>4 - Availability for key workers/ clinically vulnerable groups (non elderly) / elderly groups plus partial additional availability <br>5 - Universal availability |[OxCGRT](https://github.com/OxCGRT/covid-policy-tracker/) |
| <code>stringencyindex</code>     | Stringency Index | The Oxford Coronavirus Government Response Tracker (OxCGRT) project calculate a Stringency Index, a composite measure of nine of the response metrics. The index on any given day is calculated as the mean score of the nine metrics, each taking a value between 0 and 100. A higher score indicates a stricter response (i.e. 100 = strictest response). The nine metrics used to calculate the Stringency Index are: school closures; workplace closures; cancellation of public events; restrictions on public gatherings; closures of public transport; stay-at-home requirements; public information campaigns; restrictions on internal movements; and international travel controls. |[OxCGRT](https://github.com/OxCGRT/covid-policy-tracker/) |
| <code>uhc</code>  | UHC Index of service coverage (SCI) | UHC Index of service coverage (SCI) |Coverage of essential health services (defined as the average coverage of essential services based on tracer interventions that include reproductive, maternal, newborn and child health, infectious diseases, non-communicable diseases and service capacity and access, among the general and the most disadvantaged population). The indicator is an index reported on a unitless scale of 0 to 100, which is computed as the geometric mean of 14 tracer indicators of health service coverage. The tracer indicators are as follows, organized by four components of service coverage: 1. Reproductive, maternal, newborn and child health 2. Infectious diseases 3. Noncommunicable diseases 4. Service capacity and access See the 2019 monitoring report for the tracer indicator within each component. | [WHO](https://www.who.int/data/gho/data/indicators/indicator-details/GHO/uhc-index-of-service-coverage) |


### Affordability
includes variables depicting the estimated relative costs of vaccination campaigns as well as the affordability of vaccines to individuals.

| Variable      | Variable Name | Variable Description  | Source |
| ------------- |-------------| -----| -----|
| <code>pricebracket_che40</code>      | Cost of vaccinating 40% of population as a percent of current health expenditure |Cost of vaccinating 40% of population as percent of current health expenditure (CHE) per capita in US$ (low income US$3.89 per dose; lower middle US$5.04 per dose; upper middle US$8.49 per dose; high income US$11.39 per dose) | [UNICEF](https://www.unicef.org/supply/covid-19-vaccine-market-dashboard) |
| <code>gap_percapita</code> | Financial gap per capita in US$ for 133 low and middle income countries (in-country delivery only) | Financial gap in achieving 70% coverage by end 2022 (per capita) (US$) for 133 low and middle income countries (cost include in-country delivery only). Estimated as of 10 January 2022. |[UNICEF](https://www.unicef.org/documents/costs-and-predicted-financing-gap-deliver-covid-19-vaccines-133-low-and-middle-income ) |
| <code>gap_gghe</code>  | Financial gap as percent of government health expenditure (in-country delivery only) | Financial gap as percent of government health expenditure (costs include in-country delivery only). Estimated as of 10 January 2022. | |[UNICEF](https://www.unicef.org/documents/costs-and-predicted-financing-gap-deliver-covid-19-vaccines-133-low-and-middle-income ) |
| <code>v3_vaccinefinancialsupportsummar</code>     | Vaccine financial support | Reports the overall approach taken to vaccine funding- whether paid by the individual or the government |[OxCGRT](https://www.bsg.ox.ac.uk/research/research-projects/covid-19-government-response-tracker) |
| <code>economicsupportindex</code>  | Economic support index | The index records measures such as income support (i.e if the government is providing direct cash payments to people who lose their jobs or cannot work) and debt relief (if the government is freezing financial obligations for households (eg stopping loan repayments, preventing services like water from stopping, or banning evictions)). It is calculated using all ordinal economic policies indicators. The index ranges between 0 and 100. A higher score indicates a higher level of government support. |[OxCGRT](https://www.bsg.ox.ac.uk/research/research-projects/covid-19-government-response-tracker) |
| <code>cost_gdp_income40</code>     | Cost of vaccinating 40% of population as percent of GDP | Cost of vaccinating 40% of population as percent of GDP (low income US$3.89 per dose; lower middle US$5.04 per dose; upper middle US$8.49 per dose; high income US$11.39 per dose) | [IMF WEO October 2021](https://www.imf.org/en/Publications/WEO/Issues/2021/10/12/world-economic-outlook-october-2021); UNDP Survey; COVAX Facility |
| <code>hdi</code>     | Human development index (HDI) | Human development index (HDI). The cutoff-points are HDI of less than 0.550 for low human development, 0.550–0.699 for medium human development, 0.700–0.799 for high human development and 0.800 or greater for very high human development. |[UNDP](http://hdr.undp.org/en/data) |
| <code>y2021NGDPDPC</code>     | Gross domestic product per capita, current prices | GDP is expressed in current U.S. dollars per person. Data are derived by first converting GDP in national currency to U.S. dollars and then dividing it by total population.|[IMF WEO October 2021](https://www.imf.org/en/Publications/WEO/Issues/2021/10/12/world-economic-outlook-october-2021) |
| <code>y2021GGXWDG_NGDP</code>   | General government gross debt |Gross debt consists of all liabilities that require payment or payments of interest and/or principal by the debtor to the creditor at a date or dates in the future. This includes debt liabilities in the form of SDRs, currency and deposits, debt securities, loans, insurance, pensions and standardized guarantee schemes, and other accounts payable. Thus, all liabilities in the GFSM 2001 system are debt, except for equity and investment fund shares and financial derivatives and employee stock options. Debt can be valued at current market, nominal, or face values (GFSM 2001, paragraph 7.110). |[IMF WEO October 2021](https://www.imf.org/en/Publications/WEO/Issues/2021/10/12/world-economic-outlook-october-2021) |
| <code>e4_internationalsupport</code>   | COVID related aid spending | Announced offers of Covid-19 related aid spending to other countries |[OxCGRT](https://www.bsg.ox.ac.uk/research/research-projects/covid-19-government-response-tracker) |
| <code>h5_investmentinvaccines</code>   | Public spending on vaccine development (USD) | Announced public spending on Covid-19 vaccine development |[OxCGRT](https://www.bsg.ox.ac.uk/research/research-projects/covid-19-government-response-tracker) |
| <code>che</code>   | Current health expenditure (CHE) per capita in US$ | Current health expenditure (CHE) per capita in US$ |[WHO](https://apps.who.int/nha/database/ViewData/Indicators/en) |


### Common
contains variables on countries’ COVID-19 morbidity and mortality burden, the progress of their vaccination campaigns and their vulnerability to the ongoing pandemic.

| Variable      | Variable Name | Variable Description  | Source |
| ------------- |-------------| -----| -----|
| <code>casescumulativetotalper100000pop</code>   | Cases - cumulative total per 100000 population | Cases - cumulative total per 100000 population |[WHO](https://covid19.who.int/info/) |
| <code>casesnewlyreportedinlast7daysper</code>   | New confirmed cases reported in the last 7 days per 100,000 population. | New confirmed cases reported in the last 7 days per 100,000 population. |[WHO](https://covid19.who.int/info/) |
| <code>deathscumulativetotalper100000po</code>   | Deaths - cumulative total per 100000 population | Deaths - cumulative total per 100000 population |[WHO](https://covid19.who.int/info/) |
| <code>total_vaccinations_per100</code>   | Cumulative total vaccine doses administered per 100 population | Cumulative total vaccine doses administered per 100 population |[WHO](https://covid19.who.int/info/) |
| <code>persons_vaccinated_1plus_dose_pe</code>   | Cumulative persons vaccinated with at least one dose per 100 population | Cumulative persons vaccinated with at least one dose per 100 population |[WHO](https://covid19.who.int/info/) |
| <code>persons_fully_vaccinated_per100</code>   | Cumulative number of persons fully vaccinated per 100 population | Cumulative number of persons fully vaccinated per 100 population |[WHO](https://covid19.who.int/info/) |
| <code>total_boosters_per_hundred</code>   | Total number of boosters administered per 100 people | Total number of boosters administered per 100 people |[OWID](https://github.com/owid/covid-19-data/tree/master/public/data/vaccinations) |
| <code>first_vaccine_date</code>   | Date of First Vaccine & Number of days elapsed | Date of first vaccinations & Number of days elapsed. Equivalent to start/launch date of the first vaccine administered in a country. |[WHO](https://covid19.who.int/info/) |
| <code>number_vaccines_types_used</code>   | Number of Vaccine Type used | Number of vaccine types used per country, territory, area. |[WHO](https://covid19.who.int/info/) |
| <code>informcovid19risk</code> | INFORM COVID-19 Risk Index | The INFORM COVID Risk Index is a composite index that identifies: “countries at risk from health and humanitarian impacts of COVID-19 that could overwhelm current national response capacity, and therefore lead to a need for additional international assistance”. The index ranges between values 0- 10.The Inform COVID-19 Risk index aggregates multidimensional information on COVID-related hazards and exposures (e.g. population density, WaSH availability), COVID-19-specific vulnerabilities (movement, awareness, trust, demographics and comorbidities), Socio-economic vulnerabilities (including HDI, MPI, GII, Gini, Economic Dependency Index and information on vulnerable groups) and lack of coping capacity (e.g. country preparedness, health system capacity, immunization coverage). |[INFORM Covid-19](https://drmkc.jrc.ec.europa.eu/inform-index/inform-covid-19 ) |

## Dataset Updates
Currently, the dataset is updated every Wednesday at 02:30am EST.

## Sample Analyses
Map View:
![alt text](https://github.com/UNDP-Data/Vaccine-Equity-Dashboard-Data/blob/main/Sample%20Analyses%20Images/Map%20View.png "Map View")

Scatterplot View
![alt text](https://github.com/UNDP-Data/Vaccine-Equity-Dashboard-Data/blob/main/Sample%20Analyses%20Images/Scatterplot%20View.png "Scatterplot View")


Rank View
![alt text](https://github.com/UNDP-Data/Vaccine-Equity-Dashboard-Data/blob/main/Sample%20Analyses%20Images/Rank%20View.png "Rank View")



## Changelog
On March 25, 2022, we uploaded the dataset to GitHub.

## License
All data provided by third parties and reproduced by UNDP is subject to license terms from the original third party.







