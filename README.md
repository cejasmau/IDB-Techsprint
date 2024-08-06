August 6th, 2024
IDB - Air Techsprint
Problem 3, Group 2

# Technical documentation

## Introduction

As part of the Techsprint organized by the Inter-American Development Bank, 
this project aims to enhance the information management capabilities of governments through low-code applications and self-service tools. 
The proposed solution seeks to empower non-technical users by providing them with access to advanced analytics and data discovery capabilities 
without the need for specialized software development knowledge.

This simplified approach to application development will not only strengthen decision-making processes 
but also increase transparency in governmental operations and help identify potential cases of corruption. 
By doing so, governments are expected to respond more swiftly and effectively to current challenges, 
relying on more robust and accessible data management.

## Background Information

The data sources of the project were provided by the IDB Developer team, 
which built a data repository for governments without an information management system for public spending data. 
These repositories include general information, funding sources, financial and physical data, status, execution challenges, and referred matters.

Datasets for dominican republic:
<https://idb-air-techsprint.vercel.app/datasets/investment-projects-dom>
Datasets for paraguay:
<https://idb-air-techsprint.vercel.app/datasets/general-budget-pry>
<https://idb-air-techsprint.vercel.app/datasets/investment-projects-pry>
<https://idb-air-techsprint.vercel.app/datasets/national-development-plan-pry>

Additional datasets
Dominican Republic Open Data Portal: 
<https://datosabiertos.dgcp.gob.do/opendata/tablas>
Open Contracting Data Standard:
<https://api.dgcp.gob.do/>
Dominican Republic EMERGENCIAS - Procesos de Compras: 
<https://api.dgcp.gob.do/opendata/emergencia/procesos.csv>
Dominican Republic EMERGENCIAS - Contratos de Compras: 
<https://api.dgcp.gob.do/opendata/emergencia/contratos.csv>
Paraguay Open Data Portal: 
<https://www.contrataciones.gov.py/datos/>
Paraguay Open Contracting Data Standard: 
<https://data.open-contracting.org/es/publication/63>

## Tools and environmnet

- Rstudio: Provides an integrated environment for data analysis, statistical modeling, and visualization.
Supports a vast ecosystem of packages tailored for diverse analytical tasks, allowing the team to leverage existing libraries for quick and reliable solutions.
As an open-source tool, it is accessible to all team members, ensuring consistent and cost-effective access during and after the techsprint.

- Github: Has a robust version control, enabling multiple team members to collaborate effectively, track changes, and manage contributions in real-time.
 Integrates easily with RStudio and ensures that all code, documentation, and updates are centrally stored and accessible, 
promoting transparency and ease of communication within the team.

- Shiny (Rstudio Package): Allows the creation of interactive web applications directly from R, 
making it easy to develop user-friendly interfaces for non-technical stakeholders.
Capabilities to generate real-time, dynamic visualizations enable users to interact with data intuitively, enhancing decision-making and data exploration.
Can be rapidly deployed online or within a local network, making them accessible to end-users without requiring complex infrastructure or technical expertise.

## Data analysis and Workflow

- Data Import: Instructions for importing the datasets into RStudio.
- Data Cleaning: Describe any data cleaning processes, including code snippets.
- Data Transformation: Outline any data transformation techniques used.
- Visualization Techniques: Discuss the visualizations used (e.g., graphs, charts, maps), including why they were chosen and what they illustrate.
- Code Samples: Provide annotated code snippets that demonstrate how to perform the analysis and create the visualizations.

## Results and Insights

- Findings: Discuss the main findings from the data analysis.
- Visualizations: Include the visualizations created, along with interpretations of what they reveal about the building projects.
- Implications: Explain the implications of these findings for the building projects in Paraguay and the Dominican Republic.

## Challenges and Solutions

- Technical Challenges: Describe any technical challenges encountered during the project.
- Solutions: Outline how these challenges were addressed.

## Conclusion

- Summary: Recap the project’s goals, methodologies, and key findings.
- Future Work: Suggest possible extensions or future directions for the project.

## Appendices

- Additional Resources: Include any additional materials such as full code scripts, datasets, or references.
- Glossary: Define any technical terms or jargon used in the document.
- References: List any external sources referenced in the document.
