# Regression
SAMPLE
The sample is from the first wave of the National Epidemiologic Survey on Alcohol and
Related Conditions (NESARC), the largest nationwide longitudinal survey of alcohol and
drug use and associated psychiatric and medical comorbidities. Participants (N=43,093)
represented the civilian, non-institutionalized adult population of the United States and
included persons living in households, military personnel living off base, and persons
residing in the following group quarters: boarding or rooming houses, non-transient hotels
and motels, shelters, facilities for housing workers, college quarters, and group homes. The
NESARC included over sampling of Blacks, Hispanics and young adults aged 18 to 24 years.
The data analytic sample for this study included participants 18-25 years old who reported
smoking at least 1 cigarette per day in the past 30 days (N=1,320).

PROCEDURE
Data were collected by trained U.S. Census Bureau Field Representatives during 2001–
2002 through computer-assisted personal interviews (CAPI). One adult was selected for
interview in each household, and interviews were conducted in respondents’ homes
following informed consent procedures.

MEASURE
There are two variables :1)S2AQ21A HOW OFTEN DRANK ANY ALCOHOL DURING PERIOD OF HEAVIEST DRINKING
2)S1Q6A HIGHEST GRADE OR YEAR OF SCHOOL COMPLETED.
To better understand the model I rename S2AQ21A as 'alcoholic_score' that takes values from 1 to 10 where 1 was the highest and 99 which rapresents unknown values and S1Q6A as 'school_level' that takes values from 1 to 14 where 14 was the highest. I drop all Nan values.
I divided the sample into three groups in relation to their school_level and Printed the percentages of alcolist that belongs to each group.I considered alcolist the ones with alcolic_score <4.
