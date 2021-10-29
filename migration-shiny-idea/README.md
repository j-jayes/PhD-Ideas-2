## Codes for census data from IPUMS International

### Occupational codes

OCCISCO_codes <- tibble(
  
  codes = c(1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 99),
  descriptions = c(
    "Legislators, senior officials and managers",
    "Professionals",
    "Technicians and associate professionals",
    "Clerks",
    "Service workers and shop and market sales",
    "Skilled agricultural and fishery workers",
    "Crafts and related trades workers",
    "Plant and machine operators and assemblers",
    "Elementary occupations",
    "Armed forces",
    "NIU (not in universe)"
  )
)

### Household types

HHTYPE_codes <- tibble(
  
  codes = c(1, 2, 3, 4, 6, 7, 8, 11, 99),
  descriptions = c(
    "One-person household",
    "Married/cohab couple, no children",
    "Married/cohab couple with children",
    "Single-parent family",
    "Extended family, relatives only",
    "Composite household, family and non-relatives",
    "Non-family household",
    "Group quarters",
    "Unclassifiable"
  )
  
)