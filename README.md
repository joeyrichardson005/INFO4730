# AI and Cultural Heritage: Digital Repatriation of Artifacts

## Project Purpose
The purpose of this project is to collect and archive metadata related to cultural heritage artifacts to analyze trends in digital repatriation efforts. This repository specifically focuses on how AI tools such as image recognition and provenance tracking assist in identifying artifact origins and automating legal documentation.

## Metadata Sources
The data in this repository was collected and structured from the following cultural heritage archives:
* **UNESCO Digital Heritage Database** 
* **Smithsonian Open Access** 
* **British Museum Collection** 

## Dataset Fields
The `metadata.csv` file includes the following standardized fields:
1. **Artifact Name**: The common name of the object.
2. **Origin**: Country or region of origin.
3. **Date of Creation**: Estimated time of manufacture.
4. **Description**: Brief physical or historical context.
5. **Current Location**: The museum or archive currently holding the item.
6. **Ownership History**: Known provenance and chain of custody.
7. **Repatriation Status**: Current state of return (Requested, In Progress, or Completed).
8. **AI Usage**: The specific AI technology applied to the repatriation case (Image Recognition).

## Repository Structure
* `/Global-Repatriation-Dataset`: Contains the full collection of 5 artifacts.
* `/Exhibits/British-Museum-Claims`: A sub-folder containing artifacts specifically located in the British Museum to analyze institutional patterns.
