# GENEVIC: Supplementary Materials

## Overview
This repository contains all supplementary materials to support the project "GENEVIC".
### Diagrammatic Overview

Below is a diagram describing the workflow between the three functionalities of GENEVIC and the back-end tech-stack:

![GENEVIC Overview Diagram](Architecture_Workflow_Schema.png)
Workflow overview between the front-end user interface and the back-end architecture of GENEVIC: (i) User prompts from the interface are sent to the back-end for processing and then, (ii) Generated output is sent back to the user. The backend comprises common AI services, supported by data tools exclusive to each of the three functionalities: PGS Chat (I), GENEAPI Chat (II), and Literature Search (III). The user prompts: Prompt Ia, Prompt IIa, Prompt IIb, Prompt IIIa and Prompt IIIb generate GENEVIC outputs: Output Ia, Output IIa, Output IIb, Output IIIa and output IIIb, respectively.
#### Contents:

- **Database:**
  - **PGS Rank Database Schema Diagram** (JPG and PDF formats): 
    - Diagrammatic representation of the database's tables, indices, key constraints, and relationships.
  - **PGS Rank Database File** (.db file): 
    - A sample database of reduced size, featuring only the top 300 genes—100 each for Alzheimer's, Schizophrenia, and Cognitive traits. This subset is used to deploy our application "GENEVIC" in the Streamlit community cloud.

- **Test Runs:**
  - **PGS Chat**:
      - **ExamplePrompts_PGSChat.pdf**: Prompt suggestions for testing the application page, "PGS Chat"
      - **Screenshots_pgschat.png**: Screenshot for a test case--user input and corresponding output--for testing the application page, "PGS Chat"
  - **GeneAPI Chat**:
      - **ExamplePrompts_GeneAPIChat.pdf**: Prompt suggestions for testing the application page, "Gene API Chat"
      - **Screenshots_geneapichat.png**: Screenshot for a test case--user input and corresponding output--for testing the application page, "Gene API Chat"
   - **Literature Search**:
      - **ExamplePrompts_LiteratureSearch.pdf**: Prompt suggestions for testing the application page, "Literature Search"   
      - **Screenshots_litsearch.png**: Screenshot for a test case--user input and corresponding output--for testing the application page, "Literature Search"
  - **CompiledScreenshots.png**: Overview of Genevic Architecture with the compiled sample test runs for each of the three functionalities.
  - **TestRuns_explained.pdf**: Includes motivation, background, and detailed navigation guide of GENEVIC, including explanation of each test run's screenshot.

- **Tutorial:**  
  - **Azure Open AI Documentation.pdf**: Instructions on how to subscribe to Azure Open AI services.
  - **InstallationGuide.md**: Instructions to install and run the application "GENEVIC" on the local host as well as through the weblink.
  - **TSHOOT.md**: A troubleshooting guide for the usual problems faced while installing the pre-requisites and other required backed software and subsequently running "GENEVIC" on the local host.
  - **NavigationTutorial.md**: Link to a video tutorial simulating an example run of "GENEVIC", designed to facilitate easy access and navigation through the application.

