# DataSHIELD
In this folder, you will find a series of packages developed by the ISGlobal team specifically for the DataSHIELD platform. Each package serves a unique purpose, offering tailored functionality to enhance the capabilities of the DataSHIELD ecosystem. For a comprehensive understanding, we provide a concise overview of each package's below.


- dsOMOP: This package facilitates interaction with remote databases in the OMOP CDM format from a DataSHIELD environment. It is responsible for fetching and transforming data from databases into a user-intelligible table format, integrated into the DataSHIELD workflow to ensure compliance with the DataSHIELD security model.
- dsOMOPClient: This package enables users to invoke server-side functions from the `dsOMOP` package, which perform fetching and transforming of data from OMOP CDM databases, integrating these operations into the DataSHIELD workflow.
- dsOMOPHelper: This package provides a set of functions to help the user to work with the `dsOMOPClient` package in DataSHIELD. It provides plug-and-play functionalities for data selection and fetching, streamlining interactions with most simple use cases.