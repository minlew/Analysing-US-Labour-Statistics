# Analysing US Labour Statistics

## Project Description
The National Longitudinal Survey of Youth 1997-2011 dataset is one of the most important databases available to social scientists working with US data. It allows scientists to look at the determinants of earnings as well as educational attainment, ethnicity, sex, and other factors.

### Dataset content:

#### NLSY97_Subset.csv
* FEMALE: Sex of respondent (0 if male, 1 if female)
* MALE: Sex of respondent (1 if male, 0 if female)
* ETHBLACK: Black ethnicity
* ETHHISP: Hispanic ethnicity
* ETHWHITE: Non-black, non-Hispanic ethnicity
* AGE: Age of the respondent in 2011
* BYEAR: Year of birth
* HEIGHT: Height in inches, measured in 2004
* WEIGHT04: Weight in pounds, measured in 2004
* WEIGHT11: Weight in pounds, measured in 2011
* S: Years of schooling (highest grade completed as of 2011)
* EDUCPROF: Professional degree
* EDUCPHD: Doctorate degree
* EDUCMAST: Master's degree
* EDUCBA: Bachelor's degree
* EDUCAA: Associate's (two-year college) degree
* EDUCHSD: High school diploma
* EDUCGED: General Educational Development certificate (HSD equivalence)
* EDUCDO: High school drop-out
* SINGLE: Single, never married
* MARRIED: Married, spouse present
* COHABIT: Cohabiting
* OTHSING: Other single status
* ASVABAR: Arithmetic reasoning (ASVAB test score)
* ASVABWK: Word knowledge (ASVAB test score)
* ASVABPC: Paragraph comprehension (ASVAB test score)
* ASVABNO: Numerical operations (speed test) (ASVAB test score)
* ASVABCS: Coding speed (speed test) (ASVAB test score)
* ASVABC: Composite of ASVABAR (with double weight), ASVABWK and ASVABPC
* ASVABC4: Composite of ASVABAR, ASVABWK, ASVABPC and math knowledge score
* VERBAL: Composite of ASVABWK and ASVABPC
* ASVABMV: NLSY constructed math verbal composite
* FAITHN: No religious faith
* FAITHC: Catholic faith
* FAITHJ: Jewish faith
* FAITHP: Protestant faith
* FAITHO: Other faith
* FAITHM: Missing value for faith
* SM: Years of schooling of biological mother
* SF: Years of schooling of biological father
* SMR: Years of schooling of residential mother
* SFR: Years of schooling of residential father
* SIBLINGS: Number of siblings
* AGEMBTH: Age of mother at respondent's birth
* MSA97NO: Not in metropolitan statistical area in 1997
* MSA97NCC: In MSA, not central city in 1997
* MSA97CC: In MSA, central city in 1997
* MSA97NK: In MSA, not known if central city in 1997
* URBAN97: Living in an urban area in 1997
* REGNE97: Census region North East in 1997
* REGNC97: Census region North Central in 1997
* REGW97: Census region West in 1997
* REGS97: Census region South in 1997
* HHINC97: Gross household income in dollars, in year prior to 1997 interview
* POVRAT97: Ratio of household income to poverty level, 1997
* PRMONM: Monitoring by mother (scale 0-16, low to high)
* PRMONF: Monitoring by father (scale 0-16, low to high)
* PRMSTYUN: Mother's parenting style, uninvolved
* PRMSTYPE: Mother's parenting style, permissive
* PRMSTYAU: Mother's parenting style, authoritarian
* PRMSTYAE: Mother's parenting style, authoritative
* PRFSTYUN: Father's parenting style, uninvolved
* PRFSTYPE: Father's parenting style, permissive
* PRFSTYAU: Father's parenting style, authoritarian
* PRFSTYAE: Father's parenting style, authoritative
* EARNINGS: Current hourly earnings in dollars reported at the 2011 interview
* HOURS: Usual number of hours worked per week, 2011 interview
* TENURE: Tenure (years) with current employer at the 2011 interview
* EXP: Total out-of-school work experience (years) as of the 2011 interview
* COLLBARG: Pay set by collective bargaining, 2011
* JOBS: Number of jobs, as of 2011 interview
* CATGOV: Employment category - Government
* CATPRI: Employment category - Private sector
* CATSE: Employment category - Self-employment
* CATNPO: Employment category - Non-profit organization
* CATMIS: Employment category - Missing value
* MSA11NO: Not in metropolitan statistical area in 2011
* MSA11NCC: In MSA, not central city in 2011
* MSA11CC: In MSA, central city in 2011
* MSA11NK: In MSA, not known if central city in 2011
* URBAN: Living in an urban area in 2011
* REGNE: Census region North East in 2011
* REGNC: Census region North Central in 2011
* REGW: Census region West in 2011
* REGS: Census region South in 2011

### Technologies
* Python
* Jupyter Notebook
* Google Colab

### Python Libs
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-learn

## Getting Started
1. Clone this repository. 
2. Create virtual environment.
3. Install [requirements](requirements.txt).
4. Run [script](Analysing_US_Labour_Statistics.ipynb) in Jupyter Notebook or Google Colab.
