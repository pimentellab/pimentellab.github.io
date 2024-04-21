# Style guide for Pimentel Lab Publications.
- last updated 04/20/23 by Jingyou Rao

# Style Guide: Publications
## All sections
  - Indent with two spaces
  - Use double quotes for all string entries

# Title
- Only bold the first word and proper nouns
- Do not include a period at the end of the article title

# Authors
- Bold lab member names using the following format: **Last FM**
- Use one pair of double asterisks when multiple Pimentel lab members appear sequentially: **Young ID, Diaz RE, Liu LL**
- Use &#42; to add an asterisk denoting co-first/corresponding author. Otherwise, bolding of names using **Surname FM** will break.
- Do not include a period at the end of the author list

# Images and PDFs
- All images and PDFs should be named using the following convention: "YYYY_FirstAuthorSurname"
- Leave PMID and PMCID blank until an ID is assigned.
- Remove any sections that are not relevant to your publication (PDB, data, Zenodo, Github repo, etc).

# Additional Links

# Example below
---
title: "Title of article"
authors: "**Surname FM**, Surname FM, **Pimentel H**"
journal: #"Journal Name" #Leave blank until accepted at journal
pub_date: #"YYYY-MM-DD" #Change from Biorxiv submission date to date accepted at journal
image: "/static/img/pub/YYYY_SurnameFirstAuthor.png" Minimum dimensions TBD
pmid: #"########"
pmcid: #"PMC#######"
biorxiv_version: "YYYY.MM.DD.######v1"
pdbs:
  - #"PDB_ID" #PDB IDs must be in all caps
paired_maps_and_models:
  - pdb: #"PDB_ID" #PDB IDs must be in all caps
    emdb: #"#####"
paired_maps_and_models_and_data:
  - pdb: #"PDB_ID" #PDB IDs must be in all caps
    emdb: #"#####"
    empiar: #"#####"
data:
  - #"10.1101/2023.10.24.562292" #'doi:' prefix will be added automatically
zenodo:
  - code: #"10814911"
    description: #"rosace code at time of journal submission"
github:
  - url: #"pimentellab/rosaace"
    description: #"rosace v1.0"
links:
  - name: "Pimentel lab @ UCLA"
    url: "https://pimentellab.com"
  - name: "Willow lab @ UCSF"
    url: "https://www.wcoyotelab.com/"
  - name: "Celebratory Tweetstorm from First Surname"
    url: "https://x.com/JingyouR/status/1718993636279669176"
---