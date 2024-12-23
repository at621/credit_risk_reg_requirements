### Credit Risk Modelling Regulatory Requirements

This repository contains regulatory requirements for credit risk modelling in a CSV file. The included references are:

1. **Capital Requirements Regulation (CRR): REGULATION (EU) No 575/2013**  
2. **EBA Guidelines on the application of the definition of default under Article 178 of Regulation (EU) No 575/2013**  
3. **EBA Guidelines for PD and LGD estimation**  
4. **Final Report Guidelines for the estimation of LGD appropriate for an economic downturn (‘Downturn LGD estimation’)**  
5. **Guidelines on the estimation of LGD appropriate for an economic downturn (‘Downturn LGD estimation’)**  
6. **Final Draft Regulatory Technical Standards on the specification of the nature, severity and duration of an economic
   downturn in accordance with Articles 181(3)(a) and 182(4)(a) of Regulation (EU) No 575/2013**  
8. **ECB Guide to internal models, 2024**

> **Note**  
> This document contains arbitrary choices and excludes tables, figures and footnotes. Use only for prototyping.

---

#### Recommended Usage with ChatGPT
When using this repository with ChatGPT, it is strongly recommended to create additional indices for pre-filtering.   
This helps reduce the scope of your queries and can significantly lower computation costs.  

#### Usage Instructions

Below is a simple example of how to load the CSV file using Python’s **pandas**:

```python
import pandas as pd

# Load the CSV file
reg_requirements = pd.read_csv('eu_modelling_requirements.csv', sep=r'|', engine='python')

# Preview the first two rows
reg_requirements.head(2)
