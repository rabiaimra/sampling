# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#2`

Describe the purpose of your survey:
```
The purpose of this survey is to understand the priorities, concerns, and preferences of Canadian voters in the final month of the federal election campaign. Insights from this survey will help the party tailor its messaging, policy emphasis, and strategies to maintain voter support and maximize its chances of winning.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target Population: Eligible voters across Canada, aged 18 and over, who intend to vote in the upcoming federal election.

Sampling Frame: A national database of registered voters, supplemented with publicly available phone and email.

Sampling Units: Individual registered voters.

Observational units: Same as sampling units in our study - Individual registered voters

Sampling Strategy: A stratified random sampling approach will be used, with strata defined by province/territory, age group, and urban/rural residence to ensure geographic and demographic representation which are crucial in elections. 

We will stratify based on these 3 characteristics (province/territory, age group, and urban/rural residence). So, we will have the combination of these 3 characteristics in each strata such as: 
Ontario - Age 25-34 - Urban
Ontario - Age 25-34 - Rural
Ontario - Age 35-49 - Urban 
...

We'll have 13 provinces, 5 age groups (18-24, 25-34, 35-49, 50-64, 65+) and 2 categories (Urban or Rural). So, we'll have 13 * 5 * 2 = 130 strata in total. 
Then we'll determine the population proportion in each strata and allocate our sample size to each strata. Let's say we want to survey 2,000 people total. We'll allocate total sample size (2,000) to each strata based on its population proportion. 

Now, we know how many people we want from each strata. Within each specific strata, we randomly select that many people from our sampling frame for phone or online interviews. This strategy helps reduce sampling bias and ensures the results reflect Canada's diverse electorate. 
```

Your 5-10 question survey:
```
(A biref intro before questions) Thank you for taking the time to participate in this brief survey. Your feedback will help us understand what Canadians are looking for in leadership and policy direction. This survey should take about 3 minutes to complete.

1. How likely are you to vote in the upcoming federal election?

Very likely

Somewhat likely

Not very likely

Not at all likely

2. Which of the following issues is most important to you right now? (Please select up to 3 and rank them in order of importance (1 = most important))

Cost of living/inflation

Housing affordability

Healthcare access

Climate change

Job creation and economy

Immigration and refugees

Public safety and crime

Education and childcare

Other (please specify):

3. Do you feel that the current leadership of our party is effectively addressing the issues that matter to you?

Yes

No

Not sure

4. Which of the following best describes your impression of our party's leader?

Strong 

Trustworthy

Visionary

In touch with ordinary Canadians

Too political

Disconnected

None of the above
 
5. What is one thing our party could do to earn or maintain your vote?
(Open-ended)

6. Which party are you currently most likely to vote for?

[Our Party Name]

[Opposition Party A]

[Opposition Party B]

Undecided

7. Where do you get most of your political news and information?

TV news

Newspapers 

Online news sites

Social media

Friends or family

Party websites

Other: 

8. How satisfied are you with the direction the country is currently heading in?

Very satisfied

Somewhat satisfied

Somewhat dissatisfied

Very dissatisfied

9. What is your age group?

18–24

25–34

35–49

50–64

65+

10. In which province or territory do you currently reside?
(Dropdown or multiple choice with all provinces/territories)

```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: 
The sample was drawn using a stratified probability sampling design, with stratification conducted at the province and census metropolitan area (CMA) level. 

The survey design involves two stages. In the first stage, the sampling units are groups of telephone numbers. In the second stage, within each selected household, one individual aged 15 or older was randomly chosen to participate in the survey. Proxy responses were not allowed.

To address the challenge of reaching volunteers, the survey employed a technique known as rejective sampling. After identifying whether a respondent is a volunteer or not, sub-sampling is applied to those who are not volunteers. All volunteers complete the long version of the questionnaire. Non-volunteers are randomly split into two groups: one group completes the long interview, while the other completes a shorter version.

2. Sample size: The actual number of respondents (excluding rejected respondents) was 16,149. 

3. Target population: All persons aged 15 years and over in Canada, excluding residents of the Yukon, Northwest Territories and Nunavut and full time residents of institutions

4. Sampling frame: Combination of landline and cellular telephone numbers available to Statistics Canada from the Census and various administrative sources with Statistics Canada's dwelling frame (The Address Register which includes all dwellings within ten provinces). 

5. Survey mode(s): 
* Telephone interviews (both landline and cell) via computer assisted telephone interviewing 
* Online as electronic questionnaire.

6. Timeline: Data collection period : 2018-09-04 to 2018-12-28 

7. Response rate: The overall response rate is 41.9%.

8. Weights: 
Several weighting steps were applied for representability: 

* Initial weight calculation: The base weights were adjusted to account for varying probabilities of selection, recognizing that some households had a higher chance of being included in the sample.

* Scope adjustment: After excluding out-of-scope records, the remaining in-scope records retained their initial weights.

* Three-stage non-response adjustment: Weights for responding households were adjusted to represent non-responding telephone numbers. 

* Person weight calculation: For each respondent, a person-level weight was calculated by multiplying the household weight by the number of individuals aged 15 or older in that household.

* Rejective sampling adjustment: For non-volunteer respondents who were not excluded through subsampling, their person weights were multiplied by a factor to correct for the rejective sampling design.

* Adjustment of person weights to external totals

* Stratum adjustment: Person weights were adjusted within each geographic stratum (geographic area) in order to make population estimates consistent with the corresponding projected population counts. 

* Income adjustment: The weights were adjusted so that the weighted income distribution of GVP matched the 2017 CIS distribution by province.

* Province - age - sex adjustment: To adjust the weights to agree with projected province-age-sex population distributions. 

* Raking ratio adjustments

9. Data processing: Data collected by Statistics Canada under the Statistics Act. Provided as Public Use Microdata Files (PUMF) with anonymization. In order to preserve confidentiality, the PUMF was the object of additional processing steps such as donation perturbation and rounding. Documentation includes codebooks and user guides.

10. Cleaning, imputation, etc: 
* Automatic and manual edits during CATI and post‑collection (family, consistency and flow edits). 

* Verification was performed to identify and eliminate potential duplicate records and to drop non-response and out-of-scope records (age eligibility, whether the telephone number was personal and belonged to someone in the household)

* The flow editing carried out by head office followed a top down strategy. 

* In a small number of cases, records with missing or incorrect information were either corrected deterministically or imputed using other responses from the same questionnaire.

* Imputation: With few exceptions, imputations were carried out using donor records, selected based on a scoring function. When donor imputation was not feasible, mean imputation was applied using a pool of similar donor cases.

* The imputation process for the GVP survey was effective in addressing incomplete responses by leveraging data from other respondents with comparable or matching characteristics.

* Personal income: Data were obtained from the 2017 T1 Family File (T1FF) for 81.9% of respondents. For the remaining cases, missing values were imputed.

* Family income: A value was determined for 81.7% of households; missing data for the remaining respondents were also imputed.

* A number of variables on the file were derived by combining items on the questionnaire in order to facilitate data analysis. 

11. Sources of error: 
a- Sampling error: Accounted for via bootstrap variance estimates 

b- Non-sampling error: Coverage errors (imperfect coverage) and non-response. 

* Coverage error: Current frame excludes households without phones/internet. Survey estimates were adjusted (weighted) to represent all persons in the target population, including those not covered by the survey frame.

* Non-response bias: Non-response could occur at several stages in this survey. There were two stages of information collection: at the household level and at the individual level. Some non-response occurred at the household level, and some at the individual level. Total non-response was handled by adjusting the weight of households that responded to the survey to offset those that did not respond. For item and or partial non-response, donor imputation was done for certain variables. 

12. Limitations, known biases, etc: 
Territories and institutional residents excluded.
Exclusion of households without phone/internet may produce minor coverage biases.
Response bias remains possible due to modest response rate.

13. Link to documentation and any additional sources used:
https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234 
https://abacus.library.ubc.ca/dataset.xhtml?persistentId=hdl:11272.1/AB2/GBFDYG 
https://www150.statcan.gc.ca/n1/en/catalogue/45250011 
https://www150.statcan.gc.ca/n1/daily-quotidien/210126/dq210126h-eng.htm 

```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 29/06/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
