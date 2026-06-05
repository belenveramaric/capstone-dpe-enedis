# Capstone-DPE-Enedis
Analysis of Energy Performance Certificates (DPE) and real electricity consumption in France.

1. Introduction and Context
   
1.1 Energy Performance Certificates and the French Energy Transition

Residential buildings constitute a major component of energy demand in France, representing approximately 24% of total final energy consumption in 2023. Electricity accounts for the largest share of residential energy use (40%), followed by natural gas (27%), highlighting the importance of understanding household energy consumption patterns in the context of the energy transition [1] . 
At the national level, France's net greenhouse gas (GHG) emissions were estimated at 339 Mt CO₂eq in 2023, representing a 35% reduction compared with 1990 levels [2] . Although significant progress has been achieved, further emission reductions remain necessary to meet both national and European climate objectives. The building sector alone accounted for approximately 13% of France’s gross GHG emissions in 2023 and has been one of the major contributors to emission reductions over the past three decades.

As France pursues its carbon neutrality objectives under the Stratégie Nationale Bas-Carbone (SNBC), improving the energy performance of the residential building stock has become a policy priority [3] . The SNBC identifies buildings as a key sector for emissions reductions and establishes ambitious renovation targets for existing dwellings. In this context, the Diagnostic de Performance Énergétique (DPE) has emerged as a central regulatory and informational tool, providing standardized assessments of building performance while guiding renovation policies, investment decisions, and the broader decarbonization strategy.

1.2 What is the DPE?

The Diagnostic de Performance Énergétique (DPE), or Energy Performance Certificate (EPC), is a mandatory assessment required for the sale or rental of residential properties in France. Its primary objective is to inform prospective buyers and tenants about the energy efficiency and environmental performance of a dwelling [4].

The DPE assigns each property an energy rating ranging from A (most efficient) to G (least efficient), as well as a climate rating based on greenhouse gas emissions. [5] The certificate provides estimates of annual energy consumption expressed in kWhEP/m²/year and CO₂ emissions in kgCO₂/m²/year. It also includes information on the building's heating system, hot water production, ventilation, insulation characteristics, and estimated energy consumption for major end uses such as heating, cooling, lighting, and domestic hot water.

Beyond its informational role, the DPE has become a central policy tool in France's energy transition strategy. It is used to identify energy-inefficient dwellings, guide renovation decisions, and support regulations aimed at improving the performance of the residential building stock. Since July 2021, all residential DPEs are calculated using the standardized 3CL methodology, which estimates energy performance based on the physical characteristics of the dwelling rather than actual energy bills [4].

1.3 The Issue of Energy-Inefficient Housing

Particular attention has been directed toward dwellings classified as F or G under the DPE system, commonly referred to as passoires énergétiques (energy-inefficient dwellings). These buildings are generally characterized by poor thermal insulation, inefficient heating systems, and elevated energy requirements for maintaining acceptable indoor comfort conditions [6].
In recent years, the French government has implemented a series of regulatory measures through the Loi Climat et Résilience to progressively restrict the rental of the least efficient dwellings. These measures include [7]: 
2023: restrictions on the most energy-intensive G+ dwellings;
2025: prohibition of rental contracts for all dwellings classified G;
2028: extension of the ban to dwellings classified F;
2034: extension of the ban to dwellings classified E.

These regulations aim to accelerate energy renovation efforts and improve the overall efficiency of the residential building stock. As a result, the reliability and accuracy of DPE assessments have become increasingly important for homeowners, tenants, policymakers, and energy stakeholders. 

Beyond its regulatory role, the DPE has also become a key factor in real estate transactions, as it is mandatory for all property sales and rentals and forms part of the Dossier de Diagnostic Technique (DDT) provided to prospective buyers and tenants. Furthermore, financial institutions and investors may increasingly consider DPE ratings when assessing the value, risks, and long-term attractiveness of real estate assets [5]. 

The importance of the DPE extends beyond renovation policies, as recent methodological reforms have demonstrated its influence on housing markets and regulatory outcomes.  From January 2026, the primary energy conversion factor for electricity has been reduced from 2.3 to 1.9. This methodological change is expected to improve the DPE classification of approximately 850,000 electrically heated dwellings without requiring any physical renovation work. The reform aims to better reflect the relatively low-carbon electricity mix of France and highlights the significant influence that DPE calculation methods can have on building classifications, housing policies, and renovation incentives [8].

2. Literature Review: The DPE Methodology and the Energy Performance Gap

2.1 The Methodological Change of 2021: The 3CL Framework and the October Adjustments 

To understand current building assessments, academic literature must distinguish between certificates issued before and after the radical structural reform of July 2021. Prior to this date, DPE ratings frequently relied on the "invoice method" (DPE sur factures), which simply averaged past utility bills. This method was deeply flawed, as a house could receive a favorable rating simply because it sat vacant or because its occupants lived in extreme frugality. Furthermore, these older certificates mixed energy sources without separating electricity generation penalties, making them highly unreliable [8].

The 2021 reform unified all residential assessments under a single, fully standardized framework: the 3CL method (Calcul des Consommations Conventionnelles des Logements). Under this framework, energy performance is estimated strictly using the physical characteristics of the dwelling under standardized usage parameters, rather than observed historical consumption [8].
Building Envelope: Evaluates the building's physical traits: thermal insulation, glazing performance, thermal bridges, and overall building efficiency.

Technical Systems: Measures the presence and efficiency of heating, cooling, ventilation, and domestic hot water production systems.
Standardized Occupancy Assumptions: Incorporates uniform assumptions regarding occupancy schedules, indoor temperatures (e.g., standard heating baselines), and structural energy use patterns.
Legal Status (Opposabilité): Transitions the DPE from an "indicative" document to a fully enforceable legal contract. Tenants or buyers can legally challenge a landlord if the physical metrics of the building were misrepresented. 

The October 2021 Recalibration of the 3CL Method

While the 2021 reform aimed to standardize the DPE through the physical 3CL method, its initial rollout immediately exposed the flaws of using purely theoretical formulas to evaluate older properties [8]. As detailed in the Ministère de la Transition Écologique's explanatory notice, the initial July 2021 rollout generated severe, unanticipated anomalies, particularly over-penalizing older properties built before 1975. This forced the French government to issue an amending decree on October 8, 2021, to recalibrate the 3CL algorithm. This emergency update scaled back unrealistic mathematical assumptions regarding window venting, insulation defaults, and collective hot water systems that had artificially inflated energy bills and penalized historical buildings. Ultimately, this rapid regulatory shift proves that the DPE is a fluid, model-based estimate that struggles to reflect real-world dynamics.

2.2 The Energy Performance Gap

A substantial body of international research has documented persistent discrepancies between predicted and observed building energy consumption. This phenomenon is commonly referred to as the Energy Performance Gap (EPG). The EPG reflects the difference between the energy performance estimated by engineering models and the actual energy consumption recorded in occupied buildings [9]. 
The EPG arises because building energy assessments are generally based on deterministic engineering models that evaluate the physical characteristics of a dwelling under standardized operating conditions. These models typically assume uniform occupancy patterns, heating schedules, indoor temperatures, and appliance usage. In practice, however, actual energy consumption is influenced by a complex combination of behavioral, demographic, and socioeconomic factors. Households differ in their thermal comfort preferences, occupancy patterns, appliance ownership, ventilation habits, and responses to energy prices. As a result, observed consumption often deviates substantially from theoretical predictions.

Empirical evidence suggests that technical building characteristics explain only part of residential energy demand. Bakaloglou and Charlier (2018) show that socio-demographic and behavioral factors play a significant role in shaping household energy consumption, highlighting the limitations of purely engineering-based approaches [10]. More recent evidence from France further illustrates the magnitude of this issue. Analyses based on INSEE data indicate that the energy savings achieved following renovation projects may be, on average, approximately 50% lower than those initially predicted , revealing a substantial gap between theoretical expectations and realized outcomes [9].

Previous studies also suggest that the magnitude and direction of the performance gap vary according to the energy efficiency level of the dwelling. In low-performing buildings, actual consumption is often lower than predicted, a phenomenon known as the prebound effect. This effect is generally attributed to households adapting their behavior to high energy costs or poor thermal conditions by reducing heating demand and limiting energy use. Conversely, in highly efficient dwellings, observed consumption may exceed model predictions [10]. This phenomenon, referred to as the rebound effect, occurs when improvements in energy efficiency lead occupants to increase their level of comfort or consume additional energy services.

These findings suggest that residential energy consumption is shaped not only by the physical characteristics captured by energy performance certificates but also by occupant behavior and living conditions [11]. Consequently, evaluating the extent to which DPE ratings correspond to measured energy consumption remains a critical research challenge, particularly in the context of French energy renovation policies and decarbonization objectives.

3. Research Objective and Contribution
   
The literature highlights a fundamental limitation of energy performance assessments: while energy labels are widely used to inform public policy, real estate decisions, and renovation strategies, actual household energy consumption is strongly influenced by behavioral and socioeconomic factors that are not fully captured by engineering-based models. Although the Energy Performance Gap has been documented in several studies, limited empirical evidence is available regarding the extent to which French DPE classifications correspond to measured electricity consumption at scale.

This research addresses this gap by combining residential DPE data with observed electricity consumption data provided by Enedis. By linking theoretical energy performance assessments to real-world consumption measurements, the study aims to evaluate whether DPE classifications accurately reflect actual electricity use and to quantify the differences between predicted and observed outcomes.
More specifically, the analysis pursues four objectives:
To quantify the relationship between DPE classes and measured residential electricity consumption.
To assess the extent to which DPE-based consumption estimates correspond to observed consumption levels.
To estimate the potential energy savings associated with improvements in DPE classifications.

By providing empirical evidence on the relationship between theoretical energy performance ratings and actual electricity consumption, this study contributes to the ongoing debate surrounding the reliability of energy performance certificates and the existence of the Energy Performance Gap. The findings may help policymakers, energy stakeholders, and researchers better understand the strengths and limitations of the DPE as a tool for guiding renovation policies and supporting France’s long-term decarbonization objectives.

4. Data Methodology
    
4.1 Enedis Electricity Consumption Data
   
This study relies on annual residential electricity consumption data provided by Enedis, the main electricity distribution network operator in France. The dataset contains measured electricity consumption aggregated at the address level for residential buildings comprising at least ten dwellings, a threshold established to ensure compliance with privacy regulations.

The original dataset contains 1,625,434 observations covering metropolitan France. Key variables extracted from the dataset include the address, department code, number of dwellings, and total annual electricity consumption.
Because consumption values are reported at the address level, an average annual consumption per dwelling was calculated by dividing total electricity consumption by the number of dwellings associated with each address. This indicator provides a standardized measure that facilitates comparisons across buildings of different sizes.
The Enedis dataset constitutes the empirical benchmark of the study, as it reflects actual electricity consumption measured through smart meters or estimated from billing records when direct measurements are unavailable.

4. 2 DPE Data
   
The second data source consists of the French Energy Performance Certificate (DPE) database published by ADEME. Following the 2021 reform, DPE assessments are calculated using the standardized 3CL methodology, which estimates building energy performance based on physical characteristics rather than observed energy bills.
The complete database contains approximately 14 million observations. To ensure methodological consistency with the Enedis dataset, the analysis was restricted to certificates issued between July 2021 and 2024. 

Several variables were retained for the analysis. The DPE rating (A–G) serves as the primary explanatory variable, while theoretical energy consumption estimates constitute the main outcome measure. Additional variables include dwelling surface area, building type, construction year, department code, heating energy source, and disaggregated consumption estimates for heating, domestic hot water, cooling, lighting, and auxiliary uses.
Particular attention was given to the distinction between final energy (énergie finale) and primary energy (énergie primaire). Since Enedis reports measured electricity consumption in final energy units, only DPE variables expressed in final energy (EF) were retained. This choice ensures direct comparability between theoretical estimates and observed consumption measurements.

4.3 Address Standardization and Dataset Integration

A key methodological challenge of this study was the integration of the DPE and Enedis datasets, as both sources originate from different administrative systems and do not share a common unique identifier. Consequently, direct matching between observations was not possible using the raw datasets alone.

To ensure consistency and improve the quality of the matching process, address information was standardized using data from the Base Adresse Nationale (BAN), the official French national address database. The BAN provides standardized address information through open-data files, APIs, and data streams, allowing addresses originating from different databases to be harmonized according to a common national reference system. By relying on BAN-standardized addresses, both the DPE and Enedis datasets could be aligned using consistent address formats and geographic identifiers.

5. Methodology and Results are presented in 3 sections: Enedis_dpe_analysis, Merging DPE_Enedis, and, Results_DPE_Enedis

7. Limitations

While this study provides valuable macroscopic insights into the French residential energy sector, several inherent data and systemic limitations must be acknowledged:

1. Physical and Governance Divergence: Houses vs. Apartments
The operational realities of executing energetic retrofits differ fundamentally based on building typology:

Detached Houses: The DPE assesses an independent envelope and individual equipment. Renovation decisions, financing, and implementation fall under a single owner's responsibility, allowing for rapid execution.

Apartments: Individual apartment ratings are heavily influenced by collective building DPEs, shared walls, and common areas. Any structural renovation affecting the façade, insulation, or collective heating systems requires formal approval from the condominium association (copropriété). This fragmented governance makes implementation significantly slower, logicamente more complex, and often costlier, meaning theoretical DPE recommendations face much higher friction in multi-family buildings.

2. Selection Bias and Database Representativeness
As explicitly stated in official ADEME documentation, the DPE database does not cover the entire building stock and therefore it is not statistically representative of France's total housing reality. Because a DPE certificate is only legally triggered during real estate transactions (sales or new rental contracts), it suffers from a structural selection bias. Properties owned by long-term residents or those withheld from the market due to strict rental bans on energy-inefficient units (passoires énergétiques) are naturally underrepresented in the registry.

3. Spatial Granularity Loss 
A key technical constraint arises from the Base Adresse Nationale (BAN) geocoding framework. Because the BAN standardizes addresses at the building level and removes specific apartment numbers, all individual housing units within the same multi-family building collapse into an identical join_key. Consequently, this study loses the granularity needed to distinguish unique micro-units within a single structure. While this is an accepted limitation for aggregate, building-level analysis, it prevents the model from capturing unit-specific behavioral variations or micro-thermal exposures (e.g., top-floor vs. middle-floor apartments).

References:
(1) International Energy Agency (IEA). France – Energy Efficiency and Demand Indicators. Available at:
https://www.iea.org/countries/france/efficiency-demand

(2) European Environment Agency (EEA). Total Greenhouse Gas Emissions – France. Available at:
https://www.eea.europa.eu/en/europe-environment-2025/countries/france/total-greenhouse-gas-emissions

(3) French Ministry for Ecological Transition. French National Low-Carbon Strategy (SNBC). Available at:
https://www.ecologie.gouv.fr/sites/default/files/documents/Projet%20SNBC%20EN.pdf

(4) Ministry for Ecological Transition. General Presentation of the Diagnostic de Performance Énergétique (DPE). Available at:
https://rt-re-batiment.developpement-durable.gouv.fr/presentation-generale-du-dpe-a783.html

(5) Capifrance. DPE 2026: What Mandatory Property Surveys Are Required in France for a Real Estate Sale? Available at:
https://www.capifrance.fr/en/blog/dpe-2026-what-mandatory-property-surveys-are-required-in-france-for-a-real-estate-sale

(6) Ministry for Ecological Transition. Diagnostic de Performance Énergétique (DPE) Policy Page. Available at:
https://www.ecologie.gouv.fr/politiques-publiques/diagnostic-performance-energetique-dpe

(7) Le Tulle. French DPE Energy Performance Diagnostic: What Should I Know About It? Available at:
https://www.letulle.fr/ressources/actualites/french-dpe-energy-performance-diagnostic-what-should-i-know-about-it-

(8) Ministry for Ecological Transition. Notice Relative au DPE (October 2021 Reform). Available at:
https://www.ecologie.gouv.fr/sites/default/files/documents/notice_DPE.pdf

(9) Polytechnique Insights. Energy-Efficient Renovation: A 50% Discrepancy Between Projected and Measured Performance. Available at:
https://www.polytechnique-insights.com/en/columns/society/energy-efficient-renovation-a-50-discrepancy-between-projected-and-measured-performance/

(10) Bakaloglou, S., & Charlier, D. (2018). Determinants of Residential Energy Consumption and the Energy Performance Gap. FAERE Working Paper No. 2018.15. Available at:
https://faere.fr/pub/WorkingPapers/Bakaloglou_Charlier_FAERE_WP2018.15.pdf

(11) Schleich, J., et al. (2021). Energy Performance Gap and Household Behaviour. Energy Policy, 156. Available at:
https://www.sciencedirect.com/science/article/abs/pii/S0301421521003505
