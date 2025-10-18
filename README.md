# United-Healthcare-ER-Operational-Patient-Risk-Analysis-


<div align="center">
  <img src="https://github.com/David-TheAnalyst/United-Healthcare-ER-Operational-Patient-Risk-Analysis-/blob/main/Healthcare%20ER%20Report.png" alt="Flowpal Sales Dashboard Additional View" width="1000" height="600">
</div>

## **Outline:**
 
- Introduction
- Story of Data
- Data Splitting and Preprocessing
- Pre-Analysis
- In-Analysis
- Post-Analysis and Insights
- Data Visualizations & Charts
- Recommendations and Observations
- Conclusion
- References 

## **#Introduction:**

This report is a data-driven mandate to dismantle the operational bottlenecks choking our Emergency Room and compromising patient safety. The goal is to move beyond simple statistics and build a precise blueprint for targeted resource allocation, ensuring every patient journey is optimized for speed and stability.

The analysis of 450 patient admissions over five years reveals a system on the brink. The most critical failure is the 12.3 hours average duration in the ER, an unacceptably high figure that strains resources and puts lives at risk. This delay is coupled with a disturbing trend: a high frequency of patients arriving in critical, unstable states (Comatose, Unstable, BID), suggesting that crucial, life-saving care is being delivered too late. This report seeks to surgically isolate the root causes of these high-risk admissions and delayed care to save lives and maximize efficiency.

I utilized a single, comprehensive dataset detailing patient demographics, clinical urgency, and admission outcomes. The analysis leveraged comparative statistics and trend analysis to segment the 450 total admissions across key independent variables like Age Group, Race, Gender, Location, and Year.


## **Story of Data:**

This dataset is derived from the operational logs of the Emergency Department for the period 2019–2023. It documents every patient's journey from arrival to exit or transfer.

The data is structured with each row representing a single ER admission. Column’s detail critical context (Demographics, Time, Location) and outcome metrics (Status, Duration).

**Important Features and Their Significance:**

- Nature of Emergency: Would dictates the need for specialized, time-sensitive resource planning.

- Age Group: Would indicate where prevention efforts must be concentrated.

- Status during admission: stating direct measure of pre-hospital care and urgency, with high counts of patients arriving in Comatose, Unstable, or BID states.

## **Data Splitting and Preprocessing:**

The data was pre-cleaned to ensure consistency, standardizing categorical fields suchy6 as Race, Gender, Status and ensuring the Duration_in_ER field was correctly formatted for time-based calculations.

There were no complex mathematical transformations were required; the data was organized directly into grouped segments (e.g., age groups, yearly totals) for pivot table analysis.


##  **Pre-Analysis:**

This part of the project was focused on capturing the core narrative of the dataset. It gave me a high-level view of the data quality, the industry context, and what success looks like for stakeholders. 

**Data Splitting:**

**Independent Variables:** Used to segment and drive strategic insights: Age, Gender, Race, Location, Nature, Year.

**Dependent Variables:** The metrics to be optimized include: Status during admission, Duration in the ER.

**Industry Context:** Healthcare Industry, specifically focusing on Emergency Medicine and Public Health.

**Stakeholders:** Emergency Room (ER) Staff & Management, Hospital Administrators, Public Health Officials, and Community Outreach Teams.

**Value to the Industry:** Success is defined by reducing the average ER duration, stabilizing the status of patients upon admission, and improving the prediction of high-risk cases to save lives and resources.


## **In-Analysis:**

The in-analysis phase focused on Identifying the key trend and pinpointing the operational weaknesses buried with the company’s data using Pivot tables and charts. 

- Leading Clinical Threat: Stroke is the leading emergency with 72 cases, significantly higher than Trauma (69 cases) or Infection (66 cases).

- Most Vulnerable Cohort: The 46−60 age group accounts for the highest admissions at 88, making them the most vulnerable population requiring targeted preventative care.

- Operational Bottleneck: The average 12.3-hour ER stay is a strong indicator of overcrowding, resource constraints, or inefficient triage and flow management.

- Gender and Status Disparity: Males are more often admitted comatose and BID (Brought in Dead), while Females are often admitted unstable or comatose. This points to a potential difference in pre-hospital time delay or reporting symptoms between genders.

- Racial Disparity in Admissions: Asians (96 admissions) and Whites (95 admissions) show significantly higher ER admission counts compared to Hispanics/Latinos (82 admissions).

- COVID-19 Impact on Volume: Admissions dropped significantly in 2021 (73) before rebounding to 98 in 2022–2023, reflecting a clear link to external factors like pandemic dynamics or post-pandemic healthcare-seeking behavior.

- Location Risk Assessment: While the highest count is in "Other" (96) locations, public places (94) and homes (92) are almost equally significant, requiring a broad approach to community safety programs.



## **Post-Analysis and Insights:**

**Key Findings:**

- Stroke Priority: Stroke (72 cases) is the absolute top medical emergency and must be addressed with dedicated resource investment (protocols, imaging, teams).

- High-Risk Age Group: The 46−60 age group (88 admissions) is confirmed as the most vulnerable cohort, establishing the target for preventative public health campaigns.

- Critical Arrival Status: The significant number of patients arriving in unstable or comatose/BID status confirms a crisis in pre-hospital care delay, directly indicating a need for improved community first-response training and ambulance efficiency.

- Operational Inefficiency: The 12.3 hours average ER stay is confirmed as the primary bottleneck, impacting patient outcomes and hospital resource utilization.

- Gendered Risk: The data confirms that Males are more likely to arrive in the most severe states (Comatose/BID) than Females (Unstable/Comatose), suggesting gender-specific differences in health-seeking behavior or trauma exposure.

The analysis fully validated the initial assumptions about the primary threats (Stroke, 46−60 age group) and quantified the operational challenge (12.3 hours). The most significant surprise was the quantified racial distribution, where Asians (96) and Whites (95) showed the highest absolute admission numbers.


## **Data Visualizations & Charts:**

 
 <div align="center">
  <img src="https://github.com/David-TheAnalyst/United-Healthcare-ER-Operational-Patient-Risk-Analysis-/blob/main/Healthcare%20ER%20Report.png" alt="Flowpal Sales Dashboard Additional View" width="1300" height="auto">
</div>


The data is currently summarized and presented across several visualizations as seen in the accompanying dashboard for United Healthcare ER Report for 2019-2023.


**Charts and Graphs:**

- Admission Trend over the year: Shows the yearly volume fluctuating from a low of 73 (2021) to a high of 98 (2022/2023).

- Admission by Status (Donut Chart): Visually highlights the distribution of patients arriving in Comatose, Unstable, BID, and Stable states.

- Admission by Emergency Nature (Column Chart): Clearly ranks Stroke (72), Trauma (69), and Infection (66) as the top three clinical priorities.

- Admission by Age Group (Column Chart): Emphasizes the dominance of the 46−60 age group (88 admissions).

- Admission by Race (Column Chart): Ranks the highest admission rates for Asians (96) and Whites (95).

- Admission by Location (Column Chart): Ranks the highest admission rates for Asians (96) and Whites (95).


## **Recommendations:**

- The ER must prioritize specialized Stroke protocols (Code Stroke), ensuring the rapid deployment of dedicated response teams and investing in on-site imaging facilities (CT/MRI) to meet the critical time window for treatment.

- Design targeted awareness campaigns focusing on preventive care for middle-aged adults, addressing key risk factors for Stroke, Cardiac Arrest, and Trauma to reduce admissions from this 88-case cohort.

- Implement triage optimization systems, increase staffing capacity during peak hours, and explore fast-track lanes for less critical cases to immediately address the 12.3 hours duration bottleneck.

- Collaboration with community emergency services is essential to improve ambulance response times and expand public training in First Aid and CPR to stabilize patients before arrival, reducing the frequency of comatose and BID admissions.

- Launch gender-specific preventive health programs: for Males, focus on Stroke/Trauma prevention and reducing critical arrival status; for Females, emphasize early check-up campaigns and allergy management given the higher proportions in allergic reactions and cardiac arrest.

Whilst the sheer volume of admissions from the Asian (96) and White (95) communities, it reflects population density in the service area, which requires a deeper analysis into access and health-seeking behaviors within these specific groups to ensure equity in preventative strategies compared to the lower rate observed for Hispanics/Latinos (82).

## **Conclusion:**
 
The analysis confirms that the ER is operating under severe pressure, evidenced by the high admission count and the 12.3 hours average duration. The immediate focus must be on Stroke-related resource allocation and implementing flow improvements that will benefit all 450 patients annually. The high-risk 46−60 age group has been definitively isolated as the primary target for community health interventions.

The primary limitation is the lack of specific data on the socioeconomic status of the high-volume patient groups (Asian, White) and the absence of pre-hospital response time metrics, which limits our ability to fully explain the delays leading to critical arrival status.

Future Research: 
Future work must focus on a granular Time-to-Care analysis for Stroke patients to meet best-practice standards. 
Additionally, a detailed demographic study is required to understand the service utilization patterns of the Asian and White populations and why their admission rates are the highest.


## **References:**

-	United Healthcare ER Operational Data Log [(Kaggle)](https://github.com/David-TheAnalyst/United-Healthcare-ER-Operational-Patient-Risk-Analysis-/blob/main/Healthcare%20Kaggle%20dataset.csv)
-	Microsoft Excel (Analytical Tool)


<h3 align="left">Connect with me on Socials:</h3>
<p align="left">
<a href="https://linkedin.com/in/david ojo" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="david ojo" height="30" width="40" /></a>
<a href="https://twitter.com/david_ojo_1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="david_ojo_1" height="30" width="40" /></a>
<a href="https://medium.com/@davidojo2214" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg" alt="@davidojo" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/davidojo-j3v" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="davidojo-j3v" height="30" width="40" /></a>
</p>

Thanks for stopping by!

