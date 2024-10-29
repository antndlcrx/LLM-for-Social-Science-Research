# LLM-for-Social-Science-Research
A domain specific LLM that would be a fit for social science applications.


## Synthetic Sampling

### To Do and Warning Points:

- For ESS: when generating data, ensure compatibility between respondents' country and country specific variables. E.g., respondent from Latvia should get "party voted for in last election (Latvia)" variable. Political and Religion variables.

- 0-10 scale needs to be translated to text

- [country] in some questions needs be replaced with the country of respondent

- quality check: make sure no question value has "using this card"

- discrimination against respondent's social group is a special feature: it is recoded across multiple binary features that record if respondent marked discrimination by a specific demographic characteristic. Every characteristic has a feature, including answer options like "idk", "refuse", "not applicable" which are also recorded as separate features. 

- make sure numeric values are not confused with numbers denoting categories (14 minutes of internet use per week as opposed to "77" standing for "refuse to answer")
