Read Me


The CSV file contains values for the ESCS index (and related components) that were recomputed for earlier cycles to be on the same scale as the corresponding indices for PISA 2022 ("Trend ESCS"). 

The following variables are included:

• cycnt: PISA cycle and country code.
• cycle: PISA cycle (cycle 05=PISA 2012; cycle 06=PISA 2015; cycle 07=PISA 2018).
• cnt: country code (3-character).
• schoolid: school ID.
• studentid: student ID.
• oecd: 0=non-OECD country/economy; 1=OECD country/economy.
• escs_trend: trend ESCS index, comparable with the PISA 2022 ESCS. Values were standardized so that the mean is 0 and SD is 1 for OECD countries in 2022 (using senate weights).
• hisei_trend: trend HISEI score (recoded using the coding scheme used introduced in 2018).
• homepos_trend: trend HOMEPOS score (WLE), resulting from the joint calibration of an IRT model using PISA 2012-2022 data (see technical report for PISA 2022 for item parameters and other details).
• paredint_trend: trend PAREDINT score (recoded using the same coding scheme as in 2022).

Additional information:

• The hisei_trend index for Austria in 2012 is missing. The corresponding escs_trend for Austria in 2012 were computed by using the original hisei values as input. Original and trend hisei values differ only in terms of how "non-occupations" (social beneficiaries, housewives, students, pensioners,...) are treated; see PISA 2018 technical report for details. 
• For additional information, please refer to the PISA 2022 Technical Report (https://www.oecd.org/pisa/data/pisa2022technicalreport/).

If you have any questions, please send a message to edu.pisa@oecd.org.
