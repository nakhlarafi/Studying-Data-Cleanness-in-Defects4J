# Revisiting Defects4J for Fault Localization in Diverse Development Scenarios

This is the public repository for the paper: "Revisiting Defects4J for Fault Localization in Diverse Development Scenarios"

```
│
├── patterns              Dataset on individual change pattern (RQ1)
│  
├── scripts               Scripts to gather data
│
├── manual_study
│   ├── code_changes      For every bug, we provide code changes on the individual faul-triggering tests between the bug creation and resolution.
│   └─ manual.xlsx        Process and results of manual study (RQ2)
│  
├── system_stats          General statistics on the studied systems (e.g., LOC)
│  
├── timeline              Dataset on the timeline of the bug report, bug fix, and modifications on the fault-triggering tests.
│   ├── bug_fix.csv			  
│   ├── bug_report.csv			
│   └─ triggering_tests.csv 
│ 
├── bug_repository.csv    List of source repositories for studied systems
└─ fault_triggering_tests.csv     List of fault-triggering tests
```
The SBFL scores and Program Spectra files can be found here: https://doi.org/10.5281/zenodo.7922699
