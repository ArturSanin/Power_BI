# A

## Add to filters
“Add to filters” is an option in the context menu of a column in Power BI. This function automatically adds the selected column to the filter pane.
Users can choose whether the filter should apply only to the current report page or across all report pages. This feature facilitates the quick creation of page-level or report-level filters. 

## Aggregation
Aggregation is the process of summarizing a set of data into a single value. Common aggregations include summing, counting, calculating the maximum, or minimum.

## Aggregation Function
Eine Aggregationsfunktion ist eine Funktion, die eine Datenmenge oder Datengruppe zu einem einzelnen Wert zusammenfasst. Typische Aggregationsfunktionen sind Summe, Durchschnitt, Anzahl, Minimum und Maximum. Sie werden häufig zur Analyse und Verdichtung von Daten in Berichten eingesetzt.

## Aggregations Table
An aggregation table is a table created from a detailed fact table by aggregating its data (e.g., summing or counting). This reduces large data volumes and can significantly improve report performance, as fewer data need to be processed.

## App (Power BI Service)
An App in the Power BI Service is a collection of dashboards, reports, and semantic models (datasets) that can be grouped together and shared with users or groups. Apps provide an organized and accessible way to deliver a complete analytics environment.

# B

## Bridge Table
A bridge table is a helper table in the data model that is used to correctly represent many-to-many relationships between two tables – often between a fact table and a dimension table. A bridge table usually contains only key columns.



# C

## Calculated Column
A column defined using a DAX formula inside a table in the Power BI data model.

## Calculated Table
A table generated with a DAX formula that can be used just like a regular table in the Power BI data model.

## Canvas 
The canvas is the area of the report page in Power BI where visual elements and other components are added. It’s where the visual layout of the report is built and designed.

## Connector
A connector in Power BI is a connection solution that allows Power BI to access a specific data source and load data from it. This enables data from a wide variety of sources to be integrated into the Power BI data model.



# D

## Dashboard (Power BI Service)
A dashboard in the Power BI service is a single-page overview composed of tiles from various reports or datasets. Dashboards are used to summarize and monitor key metrics, provide quick insights and can only be created in the Power BI service.

## Data pane
The Data Pane in Power BI Desktop is the panel on the right side of the interface that displays all tables, columns, measures, and hierarchies from the data model. Users can drag and drop these fields into visualizations. The Data Pane offers quick access to all model objects.

## DAX query view
The DAX Query View is a dedicated interface for writing and evaluating DAX queries. It’s used to test custom DAX expressions.

## Delete from model
“Delete from model” is an option in the context menu of tables, columns, or measures in Power BI. It allows you to permanently remove the selected object from the data model. This action deletes the object from the model only, not from the data source. It is especially useful for cleaning up and optimizing the data model.

## Denormalization
Denormalization is the opposite of normalization. In this process, the data model is flattened by adding redundant information to tables. The goal is to simplify queries and, in some cases, improve performance.

## Dimension Table
A dimension table contains descriptive information used to categorize, filter, and group the facts from the fact table – such as product names, customer details, regions, or dates. It includes at least one key column that uniquely identifies each row and is linked to the fact table. Dimension tables provide the context for analysis within the data model.

## Drilldown
Drilldown is an interactive feature in Power BI that allows to navigate through hierarchical data, moving from a high-level view (e.g., year) to more detailed levels (e.g., quarter, month, day). By clicking on a visual that contains a hierarchy, users can drill deeper into the data structure to gain more granular insights. Drilldowns are commonly used in time, product, or geography hierarchies.



# E

## Enter Data 
The “Enter Data” option in Power BI Desktop allows users to manually create a new table by typing data directly into an input grid. This feature is useful for quickly adding reference tables, parameter values, or sample data to the data model without needing an external data source. The created table is automatically added to the model and can be used like any other table for relationships, visualizations, and DAX calculations.

## Explicit Measure
An explicit measure is a user-defined or Power BI-generated named calculation based on a DAX expression. It is manually created (or via a Quick Measure) and appears in the Fields pane for reuse in visuals.

# F

## Fact Table
A fact table contains the measurable values (also called facts) of a business, such as sales, costs, or quantities. It is at the center of a data model and is linked to dimension tables through key columns. The fact table is primarily used for calculations and analysis.

## Field
A field is a single column within a table. In Power BI, the term “field” is often used interchangeably with “column”, especially in the context of visualizations.

## Filter Card
A filter card is a field placed in the filter pane that acts as a filter on the visual, page, or report level. It supports different filtering types:

- **Basic filtering:** Selecting individual values to filter data.
- **Advanced filtering:** Filtering by specific criteria such as “greater than,” “contains,” “starts with,” etc.
- **Top N:** Displays the top or bottom N values based on a specific measure. This filter type is only available for filter cards applied on the visual level.

## Filter Pane
The filter pane is a section in the report view interface of Power BI, where fields can be placed to act as filters. The filter pane is divided into three parts:

- **Filters on this visual:** Apply only to the currently selected visual.
- **Filters on this page:** Apply to all visuals on the current report page.
- **Filters on all pages:** Apply across all visuals in the entire report.

## Flat Schema
A flat schema is a data modeling concept in which all facts and dimensions are combined into a single, denormalized table. There are no separate dimension tables – all information resides in one central table. Excel or CSV data sources are typical examples of this schema.

## Foreign Key 
A foreign key is a column or a combination of columns in a table that refers to the primary key of another table. Foreign keys are often stored in fact tables to link them to the relevant dimension tables used for analysis.

# G

## Galaxy Schema (Fact Constellation Schema)
The galaxy schema is a data modeling concept that consists of multiple fact tables sharing common dimension tables. This shared structure enables the analysis of different facts across the same dimensions.

## Get Data
The “Get Data” option on the Home tab (e. g. in Report view) in Power BI Desktop is the main entry point for connecting to various data sources. This feature allows users to select one or more data sources, such as files (e.g., Excel, CSV), databases, online services, or cloud platforms.

## Granularity
Granularity refers to the level of detail in a data model or table. For example, a table that records each individual sale has a higher granularity (i.e., is more detailed) than a table that summarizes daily sales. Using aggregations, it's possible to move from high granularity to lower granularity, but not the other way around.
High-granularity data enables deeper and more precise analysis, as it provides more context and differentiation.

## Group By (Power Query)
“Group By” is a function in the Power Query Editor that allows you to group rows in a table based on the value of one or more fields. You can then apply aggregations such as sum, count, minimum, or maximum to other columns. This function is often used to create summarized views of data.

## Grouping 
Grouping is a concept where data records are combined based on specific attributes, such as product, region, or time period. It often serves as the basis for aggregations



# H

## Hide
Hiding is a feature in Power BI that allows data model objects – such as columns, tables, and measures – as well as report elements like the filter pane or individual filter cards to be hidden from end users.
This ensures that only relevant elements are visible in the report or data model.

## Hierarchy
A hierarchy in Power BI is a structured arrangement of fields within a table that represents a logical sequence of levels – for example, Year > Quarter > Month > Day or Continent > Country > Region > City. Hierarchies allow to perform drill-down analysis, navigating from higher to more detailed levels. They enhance the usability and analytical depth of reports by organizing commonly used levels into a logical structure.

## Hybrid Table 
A hybrid table in Power BI is a table that combines multiple storage modes, typically Import and DirectQuery. For example, historical data may be imported (for fast performance), while current data is queried in real time using DirectQuery. This approach balances performance and data freshness.

# I

## Implicit Measure
An implicit measure is automatically generated by Power BI when a numeric column is added to a visual. Power BI applies an aggregation function (like SUM, COUNT, AVERAGE) without explicitly defining a measure. Implicit measures are not reusable and are more limited than explicit ones.

## Import Mode
The import mode is a storage mode in which data from the source is loaded and stored directly in Power BI. All data is present within the Power BI model, allowing for fast query performance since no external source connection is required during use.

## Import Model
An import model is a Power BI data model where all model tables are set to the storage mode "Import". In this model type, all data is loaded and stored directly within Power BI.

## Incremental Refresh 
Incremental refresh is a Power BI feature that updates only new or modified data in a table instead of importing the entire table each time. This approach saves resources, shortens refresh times, and enables handling of large datasets efficiently.

# J

# K

# L

## Lock Filter (Filter Card)
Lock filter is an option within a filter card in Power BI’s filter pane. When enabled, it prevents end users from changing or removing the respective filter in a published report in the Power BI Service. This feature is useful to ensure that specific filtering conditions — such as those used for data security or analytical consistency — remain enforced and cannot be altered by viewers.

# M

## M (Power Query Formula Language)
M is a functional language designed specifically for data preparation and ETL processes (Extract, Transform, Load). It is used to define, edit, and store data transformation steps. M is the programming language that powers the Power Query Editor in Power BI. All actions performed in the Power Query Editor are internally saved as M code.

## Manage Relationships
“Manage Relationships” is a feature in Power BI Desktop that allows users to view, edit, delete, or create relationships between tables in the data model. It provides a clear overview of all existing relationships and supports the structured management of those relationships within the model.

## Measure
A measure is a calculated value in the Power BI data model, created using the DAX language.

## Model view
The Model View visualizes the relationships between tables in the data model. It allows you to create, edit, or remove relationships, arrange tables, and configure properties like visibility or sort order.

# N 

## Normalization
Normalization is a process in data modeling used to eliminate redundancy (duplicate or repeatedly stored information) by splitting data into multiple logically related tables. These tables are connected through primary and foreign key relationships. In this structure, the normalized table includes a foreign key that references the primary key of another table — where the previously redundant information is now stored only once.

# O  

# P  

## Page-level filter 
A page-level filter in Power BI is a filter that applies only to a single report page. It is configured in the filter pane under the “Filters on this page” section and affects all visuals on that specific page, but not visuals on other pages of the report.
This type of filter is ideal for report pages with a specific focus or target audience.

## Paginated Report
A paginated report is a pixel-perfect, page-based report format optimized for printing or exporting lengthy, detailed content such as invoices or lists. It’s created using Power BI Report Builder and published to the Power BI service. Unlike regular Power BI reports, paginated reports are not interactive and are designed for precise formatting.

## Partition
A partition is a logically separated segment of a table that can be loaded, processed, and refreshed independently. Partitions help improve data processing efficiency, as only certain parts of a table (e.g., recent data) need frequent updates, while others (e.g., historical data) remain static. In Power BI, partitions are especially used with large tables or hybrid tables to enhance performance and data freshness.

## Power BI Report (Report)
A report in Power BI consists of one or more pages with interactive visualizations based on a semantic model (dataset). Reports offer powerful filtering and drill-down capabilities and are built in Power BI Desktop before being published to the Power BI service.

## Power BI-Dataset (Dataset)
A Power BI dataset is the original term for what is now officially called a semantic model. It represents the core data structure in Power BI, containing all imported or connected data, relationships, measures, calculations, roles, and metadata. A dataset can be reused across multiple reports and shared via the Power BI service.

## Power Query Editor
The Power Query Editor is a graphical interface in Power BI used to import, clean, and transform data. All transformations performed in the editor are recorded in the background using the M language (Power Query Formula Language) and are automatically applied when the data is refreshed.

## Primary key
A primary key is a column or a combination of columns that uniquely identifies each row in a table. In a dimension table, the primary key is used to establish relationships with other tables – such as a fact table.

# Q  

## Query (Power Query)
A query in Power BI (Power Query) is a step-by-step instruction set used to load, transform, and prepare data from a source for the data model. Each query consists of a series of transformations shown as individual steps. Queries can be linked, filtered, grouped, or combined and serve as the foundation for the resulting tables in the data model.

## Quick Measure
A Quick Measure is a predefined DAX pattern in Power BI, created through a visual interface. It allows users to easily generate common calculations like difference, percent of total, running total, or rank without writing DAX manually. In the background, it creates an explicit measure.

# R  

## Relationship
A relationship is the connection between two tables via primary and foreign keys. In Power BI, it enables filtering and combining data from multiple tables.

## Report view
The Report View is the visual workspace in Power BI Desktop where users build interactive visualizations, charts, KPIs, and dashboards. Fields from the data model can be dragged into visuals to design the report layout.

## Report-level filter 
A report-level filter applies to all pages in a Power BI report and affects all visuals across the report. It is configured in the filter pane under the “Filters on all pages” section and affects all visuals across all pages of the report.

# S

## Snowflake Schema
A snowflake schema is a data modeling concept similar to the star schema. Unlike the star schema, dimension tables in a snowflake schema can be further normalized and may have relationships with other dimension tables.

## Semantic Model
A semantic model in Power BI consists of all connected data sources, the data transformations, the relationships between tables, and all calculations (such as measures and calculated columns) created based on that data. It forms the foundation for building reports and analyzing data.

## Star Schema
The star schema is a data modeling concept in which a central fact table is linked to one or more dimension tables. The dimension tables are used to filter and group the data in the fact table. These filters and groupings directly affect measures based on the fact table, influencing how key figures are calculated and displayed in reports.



# T

## Table view
The Table view displays the data in your tables (from your Power BI data model) in a tabular format. It helps verify data, calculated columns, or measures, and supports understanding the underlying contents.

## Tabular Model 
A tabular model is a data model where data is structured and organized into tables. In Power BI, every data model is a tabular model, as data is stored in tables and relationships between these tables are defined.

## Template App (Power BI Service)
A Template App is a pre-built Power BI app that contains a predefined collection of dashboards, reports, and data models, usually provided by Microsoft or third-party vendors. These apps are typically designed for specific industries or use cases and enable quick integration and analysis of data.

## Tile
A tile is a building block of a dashboard in the Power BI service. Tiles can contain visualizations, KPIs, text boxes, images, or even entire report pages sourced from different reports or datasets. They provide a clear way to display information and can be individually formatted and positioned.

# U 

# V  

## Visualizations pane
The Visualizations Pane in Power BI Desktop is the right-side panel where you can select visual types, assign data fields, and customize the formatting of the currently selected visual.

# W  

# X  

# Y  

# Z  
