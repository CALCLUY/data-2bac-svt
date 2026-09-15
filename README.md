# Moroccan 2nd Bac SVT - Mathematics Data

Collection of 2nd Bac SVT Mathematics curriculum documents, homework assignments, and national examinations (2009–2025) scraped and formatted from AlloSchool.

## Directory Structure

```
mathematiques/
├── semestre-1/             # Semester 1 course chapters & exercises (Doc)
├── semestre-2/             # Semester 2 course chapters & exercises (Doc)
├── devoirs-corriges/       # Graded homework assignments with solutions (Doc)
└── examens-nationaux/      # National examinations & answer schemes (2009–2025)
    ├── 2009/
    ├── 2010/
    ...
    └── 2025/
```

## Structure of Examens Nationaux (2009–2025)

Each exam document includes a standardized YAML header:
```yaml
---
Type: Examen National
Année: [year]
Session: [Normale / Rattrapage]
Nature: [Sujet / Corrigé]
Source: 
---
```

All mathematical formulas are transcribed into raw LaTeX (`$...$` for inline math, `$$...$$` for block display equations).

### Overview of Exam Files

| Année | Session Normale (Sujet) | Session Normale (Corrigé) | Session Rattrapage (Sujet) | Session Rattrapage (Corrigé) | Total |
|-------|:-----------------------:|:-------------------------:|:--------------------------:|:----------------------------:|:-----:|
| 2009  | ✓                       | —                         | —                          | —                            | 1     |
| 2010  | ✓                       | ✓                         | —                          | —                            | 2     |
| 2011  | ✓                       | ✓                         | ✓                          | ✓                            | 4     |
| 2012  | ✓                       | ✓                         | —                          | —                            | 2     |
| 2013  | ✓                       | ✓                         | —                          | —                            | 2     |
| 2014  | ✓                       | ✓                         | ✓                          | —                            | 3     |
| 2015  | ✓                       | ✓                         | —                          | —                            | 2     |
| 2016  | ✓                       | ✓                         | ✓                          | ✓                            | 4     |
| 2017  | ✓                       | ✓                         | ✓                          | ✓                            | 4     |
| 2018  | ✓                       | ✓                         | ✓                          | ✓                            | 4     |
| 2019  | ✓                       | ✓                         | ✓                          | ✓                            | 4     |
| 2020  | ✓                       | ✓                         | ✓                          | ✓                            | 4     |
| 2021  | ✓                       | ✓                         | ✓                          | ✓                            | 4     |
| 2022  | ✓                       | ✓                         | ✓                          | ✓                            | 4     |
| 2023  | ✓                       | ✓                         | ✓                          | ✓                            | 4     |
| 2024  | ✓                       | ✓                         | ✓                          | ✓                            | 4     |
| 2025  | ✓                       | —                         | ✓                          | —                            | 2     |
| **Total** | **17**              | **14**                    | **12**                     | **11**                       | **54**|
