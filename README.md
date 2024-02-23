<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>AdventureWorks Cloud Migration and Analysis Pipeline</title>
</head>
<body>

    <h1>AdventureWorks Cloud Migration and Analysis Pipeline: From SSMS to Azure and Power BI</h1>

    <p>
        <strong>Summary:</strong> This repository presents a detailed account of the AdventureWorks database migration journey from an on-premises SQL Server Management Studio (SSMS) setup to a cloud-based solution using Microsoft Azure, with dynamic and insightful visualizations powered by Power BI. Designed to be future-proof, the project includes a robust pipeline that ensures any new additions to the source data are automatically replicated to our Power BI reports.
    </p>

    <h2>Major Tools and Services Used</h2>

    <h3>Data Ingestion:</h3>
    <ul>
        <li><strong>Azure Data Factory:</strong> Utilized for establishing a connection to the on-prem SQL database and orchestrating the data transfer to the cloud.</li>
    </ul>

    <h3>Data Storage:</h3>
    <ul>
        <li><strong>Azure Data Lake Storage Gen2:</strong> Acts as the centralized data storage solution, leveraging Lakehouse architecture for optimal data management.</li>
    </ul>

    <h3>Data Transformation:</h3>
    <ul>
        <li><strong>Azure Databricks:</strong> Responsible for transforming the raw data into a structured and analysis-ready format.</li>
        <li><strong>Azure Synapse Analytics:</strong> Integrates various services for a comprehensive data warehousing and analytics solution.</li>
    </ul>

    <h3>Data Visualization:</h3>
    <ul>
        <li><strong>Power BI:</strong> Employs this tool to create interactive and meaningful visualizations reflecting the processed data.</li>
    </ul>

    <h3>Security and Compliance:</h3>
    <ul>
        <li><strong>Azure Active Directory:</strong> Manages secure access to services used throughout the project.</li>
        <li><strong>Azure Key Vault:</strong> Keeps application secrets and keys secure within the Azure cloud environment.</li>
    </ul>

    <h2>Pipeline Architecture</h2>

    <p>
        The designed pipeline is not just static; it is meant to adapt to changes. It is carefully crafted to ensure that any modifications in the SSMS source are automatically detected and processed through the subsequent stages of storage, transformation, and visualization in Power BI.
    </p>

    <p>
        In this repository, we have provided comprehensive documentation, sample codes, and configurations necessary to replicate this effective cloud migration and data analysis setup. Follow along to create a similar environment that caters to your data needs.
    </p>

</body>
</html>
