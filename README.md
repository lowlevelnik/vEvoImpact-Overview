# vEvoImpact

🔗 Live Application: https://vevoimpact.cbsblab-nsut.in

A full-stack bioinformatics platform designed to assess the impact of viral evolution on RT-PCR diagnostic performance.

> Source code is maintained in a private repository due to research and intellectual property considerations. This repository documents the project's architecture, features, implementation, and results.

## Quick Demo
![demo](images/demo.mp4)

## Screenshots

### Home Page
![Home Page](images/home%20page.png)

### Sequence Upload Workflow
![Sequence Upload](images/Sequence%20Upload.png)

### Results Visualization
![Results Visualization](images/Results%20Visualization.png)


## Overview

RT-PCR remains one of the most widely used methods for detecting viral infections. However, as viruses evolve, mutations can emerge within primer and probe binding regions, potentially reducing the effectiveness of diagnostic assays.

vEvoImpact was developed to analyze viral genome datasets and identify mutations that may affect RT-PCR detection accuracy. The platform evaluates mutation frequency, maps primer and probe binding sites, and generates risk assessments to help identify more resilient diagnostic targets.

## Key Features

* Upload and process viral genome datasets in FASTA format
* Multiple sequence alignment using MAFFT
* Primer and probe binding site analysis
* Mutation frequency and mismatch detection
* Automated risk assessment and classification
* Interactive visualization of analysis results
* Support for SARS-CoV-2 and Influenza datasets

## My Contributions

I was responsible for the software implementation of the platform, including:

* Building the frontend using React and TypeScript
* Developing backend services using Flask
* Integrating sequence alignment workflows
* Implementing mutation analysis and primer mapping logic
* Designing data processing pipelines
* Creating visualizations and user interaction flows
* Handling validation, file processing, and error management

The underlying biological research framework and analysis methodology were developed under faculty guidance.

## Tech Stack

### Frontend

* React
* TypeScript

### Backend

* Python
* Flask

### Bioinformatics Tools

* MAFFT
* Smith-Waterman Alignment

## Architecture

```text
User Uploads FASTA Dataset
            |
            v
      React Frontend
            |
            v
       Flask Backend
            |
            +----> MAFFT Alignment
            |
            +----> Primer/Probe Mapping
            |
            +----> Mutation Analysis
            |
            +----> Risk Assessment
            |
            v
    Interactive Visualizations
```

## Repository Access

The source code for this project is currently private due to research and intellectual property considerations.

This repository serves as a project overview and showcases the system architecture, implementation approach, and key features of the platform.
