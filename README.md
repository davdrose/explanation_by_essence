# Explanation by essence
This repository contains the experiments, data, analyses, and figures for the paper "Explanation by essence"

<!-- The preprint can be found [here](update link) -->

__Contents__:
- [Explanation by essence](#explanation-by-essence)
	- [Introduction](#introduction)
	- [Repository structure](#repository-structure)

## Introduction

Lockean essentialism holds that people explain the characteristic features of natural kinds by appeal to hidden common causes — like DNA — that generate those features. Teleological essentialism, by contrast, proposes that people treat an entity’s purpose as part of its essence and explain its features in terms of what it is for. Across three preregistered experiments, we tested these competing accounts by examining how adults explain why members of different categories have their characteristic features. In Experiment 1, participants explained features of artifacts and biological kinds; in both cases, they overwhelmingly appealed to purposes rather than underlying causes. Experiment 2 showed that people can and do appeal to causal mechanisms such as DNA when explaining within-species differences, yet they revert to purpose-based explanations when explaining between-species differences, which prompts species-level categorization. Experiment 3, using randomly selected biological and non-living natural kinds, found that participants again favored purposes for biological kinds but invoked causes for certain non-living kinds (e.g., lead, oxygen, platinum). Together, these findings suggest that for biological kinds, which are central to theories of psychological essentialism, the explanatory connection between essence and features is primarily understood in teleological, not causal, terms.


## Repository structure

```
├── code
│   ├── R
│   ├── experiments
│   │   ├── experiment1
│   │   ├── ...
├── data
│   ├── experiment1
│   ├── experiment2
│   └── experiment3
├── figures
│   ├── diagrams
│   ├── experiment1
│   ├── experiment2
│   └── experiment3


```

- `code/` contains all the code for the experiments, analyzing data and generating figures.
  - `experiments` contains code for each experiment that was run. Pre-registrations for all experiments may be accessed below.
	- `experiment1` 
		- ([pre-registration](https://osf.io/f5yag/overview?view_only=11ba088121614716af21c2eaace0fdb6)) 
	- `experiment2` 
		- ([pre-registration](https://osf.io/dxc4z/overview?view_only=6435a782c6f9405ea03e0cb2d89e8b81)) 
	- `experiment3` 
		- ([pre-registration](https://osf.io/pnfhu/overview?view_only=21d3db8318f643df87f58c9ac4d9aa8c)) 	 
- `R` contains the analysis scripts that were used to analyze data and generate figures
	 <!-- (view a rendered file [here](https://davdrose.github.io/explanation_by_essence/)). -->
	 (view a rendered file [here](https://anonymous.4open.science/w/explanation_by_essence-D28B/)).
- `data/` contains anonymized data from all experiments
- `figures/` contains all the figures from the paper (generated using the script in `code/R/`). 

