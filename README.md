# gov_data

## Overview

The Brazilian Federal Revenue provides databases with public data from the National Registry of Legal Entities (CNPJ). These databases contain similar information to what we can see on an individual CNPJ card, along with additional data on Simple National, partners, and more. This project focuses on extracting, organizing, and utilizing these valuable datasets to perform diverse analyses, ranging from economic and market insights to investigative purposes.

-https://dados.gov.br/dados/conjuntos-dados/cadastro-nacional-da-pessoa-juridica---cnpj

## Description

This project involves the extraction and organization of comprehensive company data at both the corporate and establishment levels from the Brazilian Internal Revenue Service. The dataset includes the following information:

- **empresa:** Company registration details in level of the headquarters.
- **estabelecimento:** Analytical establishment data for each company unit (e.g., phone numbers, address, branches).
- **socios:** Partner information for each company.
- **simples:** Data related to Microentrepreneurs (MEI) and companies under the Simples Nacional tax regime.

Additionally, the project incorporates essential reference tables, such as:

- **CNAEs:** Codes and descriptions of economic activities.
- **quals:** Qualification of individuals - partners, responsible parties, and legal representatives.
- **natju:** Legal entity types - codes and descriptions.
- **moti:** Reasons for registration status - codes and descriptions.
- **pais:** Countries - codes and descriptions.
- **munic:** Municipalities - codes and descriptions.

Due to the extensive data volume, the tables **empresa**, **estabelecimento**, **socios**, and **simples** utilize indices for the `cnpj_basico` column, which serves as the primary key for linking them. This robust dataset offers immense possibilities for conducting diverse analyses, ranging from business insights to legal investigations, providing valuable knowledge to a wide range of stakeholders.

## Technologies Used

- SQL
- Microsoft SQL Server
- Python
- Pandas
