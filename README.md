# Where Do People Get News That They Trust About Politics and Inner-Group Conflict?
  Exploring how media consumption patterns shape political perceptions and intergroup attitudes using Afrobarometer data
  
  
  This project investigates how people in different social contexts obtain political information and how these information networks influence political trust and perceptions of intergroup conflict. Using Afrobarometer Round 8 survey data across multiple African countries, the analysis focuses on differences in media consumption between rural and urban populations and their relationship to political attitudes.

Rather than building predictive models, this project emphasizes exploratory data analysis (EDA) and visualization to uncover patterns in media use and political perception. The goal is to demonstrate how structured data analysis can reveal meaningful social and political dynamics.



## Research Questions
1. How do media consumption patterns differ between rural and urban populations?
2. Which information sources (social media, television, newspapers, interpersonal discussion) are most associated with political trust?
3. How do information networks relate to perceptions of intergroup conflict and social cohesion?



## Data

  Afrobarometer Dataset:

  ### Source
     - Dataset: Afrobarometer Round 8 survey
     - Coverage: 30+ African countries
     - Respondents: 40,000+ individuals
     - Unit of analysis: Individual survey respondents

 ### Key Variables
    -  Settlement type (Urban vs Rural)
    -  Age
    -  Gender
    -  Media consumption frequency:
      - Social media
      - Television
      - Newspapers
      - Discussions with friends and family

  ### Dependent Variables  
    - Political trust indicators
    - Intergroup perception measures
    - Attitudes toward social cohesion and diversity


## Data Processing and Cleaning

  
Steps performed:

1. Variable selection and dataset merging across countries
2. Recoding categorical variables (Urban/Rural, gender, media frequency)
3. Handling missing and inconsistent responses
4. Standardizing scales across media variables
5. Constructing composite trust indicators

## Methodology

### Exploratory Data Analysis (EDA)
- Distribution analysis of media consumption by settlement type
- Cross-tabulation of media sources and trust measures

### Statistical Analysis
- Comparison of rural vs urban media effects

### Evaluation
- Model interpretability


## Results

### Key Findings

- Urban respondents are more likely to rely on social media for political information.
- Rural respondents rely more on television and interpersonal discussions.
- Social media consumption is associated with lower levels of institutional trust.
- Traditional media sources correlate with higher perceived social cohesion.

### Example Model Results

| Variable | Effect on Political Trust |
|---------|--------------------------|
| Social Media Use | Negative |
| Television Use | Positive |
| Urban Residence | Mixed |
| Age | Positive |

Full results are available in `final_report.md`.
     
  




