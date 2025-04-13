# Radiotherapy Dataset Data Explained
This is a repository for the published RTDS data explained [View the PDF](./Docs/Data_Explained_RTDS.pdf)

## Background 
Cancer is a complex and significant public health issue, being a leading cause of death globally (Siegel et al., 2023; WHO, 2020). The increasing incidence of cancer, combined with an ageing population, places greater demand on healthcare services and highlights the need for effective detection, treatment, and intervention strategies.

Radiotherapy is a widely used cancer treatment that employs radiation (e.g., x-rays) to target and destroy cancer cells. It is a crucial component of many cancers treatment plans, particularly for localised cancers (CRUK, 2023). However, despite its effectiveness, radiotherapy can cause undesirable side effects and health complications. Understanding these effects is essential for improving treatment strategies and patient outcomes.

**RTDS Standard**

The RTDS, was initially known as the 'National Radiotherapy Data Set,' and was developed and implemented by Public Health England in 2009 (Dawson, 2015). Its aim was to gather technical and clinical information on patients receiving radiotherapy. The primary objectives were to:

“*To improve availability and use of data already held about treatment given to patients by radiotherapy facilities and to direct the development of systems supporting data collection and use in the small number of facilities that do not yet hold such data*” (Wells, 2015). In addition it also aims to “*collect consistent and comparable data across all NHS providers of radiotherapy services in England and Wales in order to provide intelligence for service planning, commissioning, clinical practice and research and the operational provision of radiotherapy services across England and Wales*” (Cancer Implementation Group, 2022) And as a standard requires all NHS radiotherapy providers to “*collect and submit standardised data monthly against a nationally defined dataset*”(Cancer Implementation Group, 2022).

In 2015, the NHS Wales Informatics Service (now known as Digital Health Care Wales) facilitated the introduction of RTDS in Wales. This was achieved by adopting the RTDS Management Service from England, in collaboration with the National Clinical Analysis and Specialised Applications Team (NATCANSAT), to deliver the service in Wales (Wells, 2015).

The implementation of RTDS affected three radiotherapy service centres in Wales:

- Velindre Cancer Centre, Cardiff
- Singleton Oncology Centre, Swansea
- North Wales Cancer Treatment Centre, Rhyl

Following the initial adoption period, only one Welsh radiotherapy centre was consistently submitting data. In 2016, Public Health England (PHE) took over the management of RTDS Version 5 and partnered with the Welsh Cancer Intelligence and Surveillance Unit (WCISU) to fully implement RTDS across Wales. Together, they developed a system that enabled radiotherapy centres to submit data on a monthly basis, starting with patients treated from the previous month (Cancer Implementation Group, 2022).

RTDS data submissions from each centre began on the following dates (Cancer Implementation Group, 2022, 2022):

- South West Wales Cancer Centre: April 2016
- North West Wales Cancer Centre: March 2018
- Velindre Cancer Centre: November 2018

The Welsh dataset is a subset of the 'National Radiotherapy Data Set,' focusing specifically on radiotherapy data items, with fewer demographic details. It covers all patients receiving the following types of radiotherapy:

- Teletherapy: External beam radiotherapy.
- Brachytherapy: Internal radiotherapy delivered using automated remote after loading machines.
- Other Brachytherapy: Internal radiotherapy for malignant disease (Wells, 2015).

## Purpose
The Secure Anonymised Information Linkage (SAIL) Databank is a Trusted Research Environment (TRE) that houses millions of encrypted individual-level records from a wide range of health, wellbeing, legal, and economic data providers. It covers approximately 3 million people in Wales (Lyons et al., 2009).

The RTDS is one of the datasets stored within the SAIL Databank. Its inclusion in SAIL enables the linking of RTDS data with numerous other data sources. This integration has the potential to significantly enhance our understanding of the effects and impacts of cancer on the Welsh population.

## Data Structure
Markdown containing all SQL and R code used to generate insights published in the data explained.

## Funding
This project was funded by the Cancer Research Strategy for Wales (CReSt) catalytic funding (HCRW) and the Cancer Trusted Research Environment Project (Roche).
