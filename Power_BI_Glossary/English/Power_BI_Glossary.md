# A

## Active Relationship
An active relationship is the currently used relationship between two tables in Power BI. It is represented by a solid line in the model and defines the default path for filter propagation and calculations. Only one active relationship can exist between two tables at a time. All DAX calculations use the active relationship by default unless another is explicitly specified.

## Add to filters
“Add to filters” is an option in the context menu of a column in Power BI. This function automatically adds the selected column to the filter pane.
Users can choose whether the filter should apply only to the current report page or across all report pages. This feature facilitates the quick creation of page-level or report-level filters. 

## Aggregation
Aggregation is the process of summarizing a set of data into a single value. Common aggregations include summing, counting, calculating the maximum, or minimum.

## Aggregation Function
An aggregation function is a function that summarizes a dataset into a single value. Common aggregation functions include sum, average, count, minimum, and maximum. They are often used to analyze and condense data in reports.

## Aggregations Table
An aggregation table is a table created from a detailed fact table by aggregating its data (e.g., summing or counting). This reduces large data volumes and can significantly improve report performance, as fewer data need to be processed.

## App (Power BI Service)
An App in the Power BI Service is a collection of dashboards, reports, and semantic models (datasets) that can be grouped together and shared with users or groups. Apps provide an organized and accessible way to deliver a complete analytics environment.

## ArcGIS for Power BI (Standard Visual)
The ArcGIS for Power BI visual is an advanced mapping solution integrated into Power BI that brings Esri’s GIS capabilities to your reports. It provides:

- Advanced geocoding and address resolution

- Thematic maps (choropleth), heat maps, and cluster analysis

- Data enrichment with demographic and geographic data from ArcGIS Online

- Interactive spatial tools like buffer zones, line tracing, and custom geometries

With ArcGIS for Power BI, users can perform in-depth spatial analyses and enhance reports with professional GIS features.

## Area Chart (Standard Visual)
An area chart is an extension of the line chart, where the area beneath the line is filled with color or shading to represent the magnitude or volume of a value over time. It is particularly useful for visualizing changes and trends over time, as well as for representing the cumulative total of values.

## Azure Map (Standard Visual)
An Azure Map visual integrates Bing Maps / Azure Maps services, offering advanced map displays, traffic and weather layers, heatmaps, and route visualizations. It’s ideal for interactive, data-rich maps with Azure-powered features.

# B

## Bidirectional Relationship
A bidirectional relationship allows filters to flow in both directions between related tables. This setting is useful in complex data models with multiple fact tables or many-to-many relationships, but it can also lead to unexpected filter behavior or performance issues.

## Bridge Table
A bridge table is a helper table in the data model that is used to correctly represent many-to-many relationships between two tables – often between a fact table and a dimension table. A bridge table usually contains only key columns.

## Button Slicer (Standard Visual)
The Button Slicer is a custom visual in Power BI that provides slicer functionality in the form of buttons. Instead of a traditional list or dropdown, filter values are displayed as customizable buttons that users can select singly or multiply with a click. Key Features:

- Button layout: Values appear as rectangular or rounded buttons.

- Multi-select: Supports single or multiple button selections.

- Customizable design: Button colors, fonts, and sizes can be tailored.

- Interactivity: Selections immediately update all linked visuals.

The Button Slicer is ideal for dashboards requiring user-friendly, visually engaging filters.



# C

## Calculated Column
A column defined using a DAX formula inside a table in the Power BI data model.

## Calculated Table
A table generated with a DAX formula that can be used just like a regular table in the Power BI data model.

## Canvas 
The canvas is the area of the report page in Power BI where visual elements and other components are added. It’s where the visual layout of the report is built and designed.

## Card (new) (Standard Visual)
The Card (new) visual in Power BI is the revamped version of the classic card visual that, in addition to displaying a single value, now includes miniature trend lines and delta indicators. It’s designed to present key metrics compactly while conveying recent performance at a glance. Features include:

- Single value display (e.g., revenue, count)

- Sparkline trend line under the value for short‑term insight

- Delta indicator (arrow or percentage) comparing against a prior period or target

- Customizable formatting (font size, colors, and background)

This visual merges the simplicity of a KPI card with visual cues to show not only the current value but also its direction and change.

## Card (Standard Visual)
The Card visual in Power BI displays a single metric or value prominently. It is especially useful for showing key KPIs such as revenue, totals, or averages in a compact and highly readable format. A card has no axes or categories by default and is often used to highlight individual metrics.

## Cardinality 
Cardinality defines the type of relationship between records in two tables. It indicates how many values from one table can be related to how many values in another table. Power BI supports the following types of cardinality:

- **One to one (1:1):** Each value in table A is related to exactly one value in table B, and vice versa.

- **One to many (1:\*):** A single value in table A may relate to many values in table B.

- **Many to one (\*:1):** The inverse perspective of a one to many relationship.

- **Many to many (\*:\*):**  Multiple values in table A can be related to multiple values in table B.

Cardinality is critical for understanding how relationships behave in the data model and how filters propagate across tables.

## Cardinality Reduction 
Cardinality Reduction refers to the process of decreasing the number of distinct values in a column within Power BI or data modeling in general. This can be achieved through aggregation, rounding, bucketing, or by removing unnecessary detail-level data. The main goal is to reduce model size, improve performance, and optimize query processing. High cardinality can negatively impact performance, especially in large-scale datasets.

## Circular Relationship
A circular relationship occurs when the relationships between multiple tables form a closed loop. This means two tables that are already connected—either directly or indirectly—are linked again through an additional relationship. Such loops can cause ambiguity and infinite filter chains. Therefore, Power BI prevents the creation of circular relationships in the data model.

## Clustered Bar Chart (Standard Visual)
A clustered bar chart displays the comparisons between different categories using horizontal bars. The bars for each category are placed side by side, making it easy to compare values across different groups. It is great for visualizing differences between various data groups.

## Clustered Column Chart (Standard Visual)
A clustered column chart functions similarly to the clustered bar chart, but the data is represented vertically. The categories are placed side by side in columns, allowing a simple comparison of values across different groups. This chart is ideal for multiple comparisons between various data groups in a single chart.

## Command palette (DAX query view)
The Command Palette is an option in the “Home” tab of the DAX Query View in Power BI. It displays a list of all available editing commands, including their keyboard shortcuts (if available). Users can also search for commands, making it easier and faster to perform specific actions. This feature enhances navigation and efficiency within the DAX environment.

## Comment (DAX query view)
Comment is an option in the “Home” tab of the DAX Query View in Power BI. It allows users to comment out selected DAX code, so it is ignored during execution. This feature is especially useful for debugging, testing, or temporarily disabling parts of the code for analysis.

## Connector
A connector in Power BI is a connection solution that allows Power BI to access a specific data source and load data from it. This enables data from a wide variety of sources to be integrated into the Power BI data model.

## Cross-filter direction 
Cross filter direction defines the direction in which filters are applied across a relationship between two tables. There are two options:

- **Single:** The filter flows in one direction only – typically from a dimension table to a fact table.

- **Both (Bidirectional):** The filter flows in both directions, allowing the tables to filter each other.

Bidirectional filtering is useful for complex data models or many-to-many relationships but may lead to unexpected results or performance issues.


# D

## Dashboard (Power BI Service)
A dashboard in the Power BI service is a single-page overview composed of tiles from various reports or datasets. Dashboards are used to summarize and monitor key metrics, provide quick insights and can only be created in the Power BI service.

## Data pane
The Data Pane in Power BI Desktop is the panel on the right side of the interface that displays all tables, columns, measures, and hierarchies from the data model. Users can drag and drop these fields into visualizations. The Data Pane offers quick access to all model objects.

## DAX query view
The DAX Query View is a dedicated interface for writing and evaluating DAX queries. It’s used to test custom DAX expressions.

## Decomposition Tree (Standard Visual)
The Decomposition Tree visual in Power BI is an interactive tool for breaking down data by hierarchies or attributes. It allows users to drill down into a measure (like revenue, profit, or count) step-by-step across various dimensions—such as region, product, or time period—to identify root causes, patterns, or outliers. The decomposition tree is especially useful for ad hoc exploration, where users want flexibility in choosing how data should be broken down.

## Delete from model
“Delete from model” is an option in the context menu of tables, columns, or measures in Power BI. It allows you to permanently remove the selected object from the data model. This action deletes the object from the model only, not from the data source. It is especially useful for cleaning up and optimizing the data model.

## Denormalization
Denormalization is the opposite of normalization. In this process, the data model is flattened by adding redundant information to tables. The goal is to simplify queries and, in some cases, improve performance.

## Dimension Table
A dimension table contains descriptive information used to categorize, filter, and group the facts from the fact table – such as product names, customer details, regions, or dates. It includes at least one key column that uniquely identifies each row and is linked to the fact table. Dimension tables provide the context for analysis within the data model.

## Donut Chart (Standard Visual)
A donut chart is a variation of the pie chart with a central hole, providing space for additional labels or summary metrics.

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

## Filled Map (Standard Visual)
A filled map visual colors geographic regions (e.g., countries, states, ZIP codes) according to a value. Darker or more intense colors indicate higher values for those areas.

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

## Find (DAX query view)
Find is an option in the “Home” tab of the DAX Query View in Power BI. It allows users to search for a specific string within the current DAX query. This function is useful for quickly locating expressions, variables, or functions in larger DAX code.

## Flat Schema
A flat schema is a data modeling concept in which all facts and dimensions are combined into a single, denormalized table. There are no separate dimension tables – all information resides in one central table. Excel or CSV data sources are typical examples of this schema.

## Foreign Key 
A foreign key is a column or a combination of columns in a table that refers to the primary key of another table. Foreign keys are often stored in fact tables to link them to the relevant dimension tables used for analysis.

## Format query (DAX query view)
Format Query is an option in the “Home” tab of the DAX query view in Power BI. It automatically formats the written DAX code into a structured and more readable layout. This helps improve readability and maintainability, especially for complex DAX expressions.

## Funnel (Standard Visual)
A funnel chart represents a multi-stage process where the count of items decreases at each stage. Each stage is sized proportionally to the remaining quantity.



# G

## Galaxy Schema (Fact Constellation Schema)
The galaxy schema is a data modeling concept that consists of multiple fact tables sharing common dimension tables. This shared structure enables the analysis of different facts across the same dimensions.

## Gauge (Standard Visual)
A gauge visual displays a measure relative to a target or range on a semicircular dial. It visualizes progress, utilization, or performance against predefined thresholds.

## Get Data
The “Get Data” option on the Home tab (e. g. in Report view) in Power BI Desktop is the main entry point for connecting to various data sources. This feature allows users to select one or more data sources, such as files (e.g., Excel, CSV), databases, online services, or cloud platforms.

## Goals (Preview) (Standard Visual)
The Goals visual (Preview) in Power BI allows you to visually represent goals or metrics and track their progress in real-time. It shows how well a specific metric (e.g., revenue, expenses, sales targets) is performing against a set target or threshold. The visual can display progress with color-coded indicators, such as bars, percentages, or numerical values. This helps users easily monitor performance and quickly identify whether goals are being achieved.

## Granularity
Granularity refers to the level of detail in a data model or table. For example, a table that records each individual sale has a higher granularity (i.e., is more detailed) than a table that summarizes daily sales. Using aggregations, it's possible to move from high granularity to lower granularity, but not the other way around. High-granularity data enables deeper and more precise analysis, as it provides more context and differentiation.

## Group By (Power Query)
“Group By” is a function in the Power Query Editor that allows you to group rows in a table based on the value of one or more fields. You can then apply aggregations such as sum, count, minimum, or maximum to other columns. This function is often used to create summarized views of data.

## Grouping 
Grouping is a concept where data records are combined based on specific attributes, such as product, region, or time period. It often serves as the basis for aggregations.



# H

## Hide
Hiding is a feature in Power BI that allows data model objects – such as columns, tables, and measures – as well as report elements like the filter pane or individual filter cards to be hidden from end users. This ensures that only relevant elements are visible in the report or data model.

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

## Inactive Relationship 
An inactive relationship is an additional relationship between two tables that is not used by default for filtering or calculations. It is represented by a dashed line in the model. Inactive relationships are useful when multiple relationship paths are needed (e.g., sales date vs. delivery date). They can be explicitly activated in DAX using functions like USERELATIONSHIP.

## Incremental Refresh 
Incremental refresh is a Power BI feature that updates only new or modified data in a table instead of importing the entire table each time. This approach saves resources, shortens refresh times, and enables handling of large datasets efficiently.

# J

# K

## Key Influencers (Standard Visual)
The Key Influencers visual in Power BI analyzes which fields have the greatest influence on a selected target value. It uses automated statistical analysis to identify which dimensions or categories significantly affect the chosen measure or attribute. It can show, for example, under which conditions a value tends to be high or low. This AI-powered visual helps users understand causes and relationships within their data.

## KPI (Standard Visual)
The KPI visual (Key Performance Indicator) in Power BI displays the current status of a performance metric compared to a defined target. It typically uses a measure, a target, and a time dimension (e.g., date) to show performance over time. Visual cues like colors or arrows indicate at a glance whether the current value is above, below, or meeting the goal.

# L

## Line and Clustered Column Chart (Standard Visual)
The line and clustered column chart combines a line chart with a clustered column chart. The clustered columns show the comparisons between different categories or groups, while the line follows the trend of a specific metric. This chart is useful for visualizing both the comparison of categorical data and the progression of a trend simultaneously.

## Line and Stacked Column Chart (Standard Visual)
The line and stacked column chart combines a line chart with a stacked column chart on a common axis. This combination allows for the visualization of both absolute values (via the columns) and relative trends (via the line). It is useful for showing the progression of a metric alongside a composite display of several other metrics.

## Line Chart (Standard Visual)
A line chart visualizes data points connected by a continuous line and is often used to display trends over time. It is ideal for showing changes in data values captured at regular intervals, such as sales over months or years. The line chart emphasizes the change and development of values.

## Lock Filter (Filter Card)
Lock filter is an option within a filter card in Power BI’s filter pane. When enabled, it prevents end users from changing or removing the respective filter in a published report in the Power BI Service. This feature is useful to ensure that specific filtering conditions — such as those used for data security or analytical consistency — remain enforced and cannot be altered by viewers.

# M

## M (Power Query Formula Language)
M is a functional language designed specifically for data preparation and ETL processes (Extract, Transform, Load). It is used to define, edit, and store data transformation steps. M is the programming language that powers the Power Query Editor in Power BI. All actions performed in the Power Query Editor are internally saved as M code.

## Manage Relationships
“Manage Relationships” is a feature in Power BI Desktop that allows users to view, edit, delete, or create relationships between tables in the data model. It provides a clear overview of all existing relationships and supports the structured management of those relationships within the model.

## Manage roles / Manage security roles (Modeling tab)
The "Manage Roles" option in the "Modeling" tab of Power BI provides an overview of all existing security roles in the data model. Users can:

- Create new roles.

- Edit existing roles.

- Delete roles.

Roles control data access through DAX filter expressions, which can be written using the DAX editor, or defined through a user interface.

## Many to many (\*:\*) Relationship
In a many to many relationship, multiple records in one table can relate to multiple records in another table. These relationships require careful handling, as they may lead to unexpected filter behavior.

## Map (Standard Visual)
A map visual displays geographic data as points or symbols on a world or region map. It’s used to plot locations, coordinates, or value points, often encoded by size or color.

## Matrix (Standard Visual)
The Matrix visual in Power BI is an enhanced version of the table that can display data in a hierarchical structure – similar to a PivotTable in Excel. It supports expanding and collapsing categories, showing subtotals, and placing values across rows and columns. It's ideal for analyzing multidimensional data.

## Measure
A measure is a calculated value in the Power BI data model, created using the DAX language.

## Model view
The Model View visualizes the relationships between tables in the data model. It allows you to create, edit, or remove relationships, arrange tables, and configure properties like visibility or sort order.

## Multi-row Card (Standard Visual)
The Multi-row Card visual in Power BI displays multiple measures or values simultaneously in a structured layout – each row represents a field with its corresponding value. It is ideal for showing multiple KPIs side by side, providing a compact overview of key metrics. Unlike the single Card, which shows only one value, the Multi-row Card presents several values at once.

# N 

## Narrativ (Standard Visual)
The Narrative visual in Power BI uses Artificial Intelligence (AI) to automatically generate textual descriptions of the data presented. It analyzes the visualizations and provides automatically generated explanatory text to help users understand the data shown. The Narrative visual offers a narrative context that summarizes key trends and patterns in the data. It can be a valuable tool for decision-makers to quickly and easily interpret the data.

## Normalization
Normalization is a process in data modeling used to eliminate redundancy (duplicate or repeatedly stored information) by splitting data into multiple logically related tables. These tables are connected through primary and foreign key relationships. In this structure, the normalized table includes a foreign key that references the primary key of another table — where the previously redundant information is now stored only once.

# O  

## One to many (1:\*) / Many to one (\*:1) Relationship
The one to many relationship is the most common type in Power BI. A single record in the first table is related to multiple records in the second table. Filters propagate from the “one” side to the “many” side – typically from a dimension table to a fact table.

## One to one (1:1) Relationship 
A one-to-one relationship means that each record in Table A corresponds to exactly one record in Table B – and vice versa. These relationships are rare but useful when logically connected data is split into separate tables.

# P  

## Page-level filter 
A page-level filter in Power BI is a filter that applies only to a single report page. It is configured in the filter pane under the “Filters on this page” section and affects all visuals on that specific page, but not visuals on other pages of the report. This type of filter is ideal for report pages with a specific focus or target audience.

## Paginated Report
A paginated report is a pixel-perfect, page-based report format optimized for printing or exporting lengthy, detailed content such as invoices or lists. It’s created using Power BI Report Builder and published to the Power BI service. Unlike regular Power BI reports, paginated reports are not interactive and are designed for precise formatting.

## Paginated Report (Standard Visual)
The Paginated Report visual in Power BI is designed for multi-page report display and export. It’s ideal for print-ready, row-oriented layouts (such as invoices or listings) that require precise control over page breaks, headers/footers, and table formatting. Paginated reports are created with the Power BI Report Builder and can be embedded and distributed within the Power BI service.

## Partition
A partition is a logically separated segment of a table that can be loaded, processed, and refreshed independently. Partitions help improve data processing efficiency, as only certain parts of a table (e.g., recent data) need frequent updates, while others (e.g., historical data) remain static. In Power BI, partitions are especially used with large tables or hybrid tables to enhance performance and data freshness.

## Pie Chart (Standard Visual)
A pie chart represents the proportions of a whole as slices of a circle. The size of each slice is proportional to its category’s value.

## Power Apps for Power BI (Standard Visual)
The Power Apps for Power BI visual enables embedding a Power App directly within a Power BI report. Users can interact with custom, responsive apps to view, edit, or add new records based on the report’s data—all without leaving the Power BI interface. The integration supports bidirectional data flows between Power BI and the Power App.

## Power Automate for Power BI (Standard Visual)
The Power Automate for Power BI visual is an action visual that lets you trigger Power Automate flows directly from within a Power BI report. Users can embed trigger buttons that, when clicked, automatically run predefined automations—such as sending notifications, updating records, or initiating approval processes. The visual supports passing context data from Power BI into the flow for further processing.

## Power BI Report (Report)
A report in Power BI consists of one or more pages with interactive visualizations based on a semantic model (dataset). Reports offer powerful filtering and drill-down capabilities and are built in Power BI Desktop before being published to the Power BI service.

## Power BI-Dataset (Dataset)
A Power BI dataset is the original term for what is now officially called a semantic model. It represents the core data structure in Power BI, containing all imported or connected data, relationships, measures, calculations, roles, and metadata. A dataset can be reused across multiple reports and shared via the Power BI service.

## Power Query Editor
The Power Query Editor is a graphical interface in Power BI used to import, clean, and transform data. All transformations performed in the editor are recorded in the background using the M language (Power Query Formula Language) and are automatically applied when the data is refreshed.

## Primary key
A primary key is a column or a combination of columns that uniquely identifies each row in a table. In a dimension table, the primary key is used to establish relationships with other tables – such as a fact table.

## Python Visual (Standard Visual)
The Python Script Visual in Power BI allows the creation of custom visuals using Python code. A Python script is executed within the visual to produce charts, plots, or other graphical outputs based on the selected fields. This visual is especially useful for machine learning, statistical analysis, or specialized visualizations beyond the standard visuals.

# Q  

## Q&A (Standard Visual)
The Q&A visual in Power BI allows users to ask questions about their data in natural language. Based on the posed questions, Power BI automatically generates visualizations to display the requested information. The Q&A visual uses Artificial Intelligence (AI) and the underlying data structure to find and present answers. This feature offers an intuitive and user-friendly way to quickly gain insights without having to manually apply filters or create charts.

## Query (Power Query)
A query in Power BI (Power Query) is a step-by-step instruction set used to load, transform, and prepare data from a source for the data model. Each query consists of a series of transformations shown as individual steps. Queries can be linked, filtered, grouped, or combined and serve as the foundation for the resulting tables in the data model.

## Quick Measure
A Quick Measure is a predefined DAX pattern in Power BI, created through a visual interface. It allows users to easily generate common calculations like difference, percent of total, running total, or rank without writing DAX manually. In the background, it creates an explicit measure.

# R  

## R Script Visual (Standard Visual)
The R Script Visual in Power BI allows the creation of custom visuals using the R programming language. An R script is executed within the visual to generate charts and plots based on the selected fields. This visual is particularly useful for statistical analysis, advanced data visualizations, and highly customized charts.

## Relationship
A relationship is the connection between two tables via primary and foreign keys. In Power BI, it enables filtering and combining data from multiple tables.

## Relationship Editor / Edit Relationship
The Relationship Editor in Power BI’s Model View is a dialog box used to create or edit relationships between two tables. Using the Edit Relationship function, you can:

- Select the linked tables and columns.

- Define the cardinality.

- Set the cross filter direction (single or both).

- Choose whether the relationship is active or inactive.

The Relationship Editor is a key tool for managing and customizing the data model structure.

## Replace (DAX query view)
Replace is an option in the “Home” tab of the DAX Query View in Power BI. It allows users to find a specific string in the current DAX code and replace it with another string. This feature is useful for quickly modifying or correcting parts of the code.

## Report view
The Report View is the visual workspace in Power BI Desktop where users build interactive visualizations, charts, KPIs, and dashboards. Fields from the data model can be dragged into visuals to design the report layout.

## Report-level filter 
A report-level filter applies to all pages in a Power BI report and affects all visuals across the report. It is configured in the filter pane under the “Filters on all pages” section and affects all visuals across all pages of the report.

## Ribbon Chart (Standard Visual)
A ribbon chart displays changes in the ranking of different categories over a timeline. The width of each ribbon represents the relative magnitude of the value, while its vertical position shows the rank across time.

## Role
A role in Power BI defines a group of users for whom specific security rules (e.g., Row-Level Security) apply. Roles are configured in the data model and contain DAX filter expressions that determine which data a user is allowed to see. After publishing the report to the Power BI service, users can be assigned to a role. This ensures that each user group sees only the data relevant to them.

## Row-Level_Security (RLS)
Row-Level Security (RLS) is a security feature in Power BI that restricts access to specific rows of data based on user roles. Using DAX filter expressions within defined roles, it controls which data a user can see when viewing the report in the Power BI service. RLS ensures that sensitive information is only visible to authorized users, even when reports are shared.

# S

## Scatter Chart (Standard Visual)
A scatter chart displays the relationship between two numerical variables as points in a coordinate plane. Optionally, a third variable can be encoded by the size of each point (bubble chart).

## Semantic Model
A semantic model in Power BI consists of all connected data sources, the data transformations, the relationships between tables, and all calculations (such as measures and calculated columns) created based on that data. It forms the foundation for building reports and analyzing data.

## Slicer (Standard Visual)
The Slicer visual in Power BI is an interactive control that allows users to filter reports by selecting values from a specific column. It enables simple and visual filtering of the displayed data, such as choosing a date range, categories, or specific items. By default, slicers affect all visuals on the current page, but their filter effect can be customized or synchronized.

## Snowflake Schema
A snowflake schema is a data modeling concept similar to the star schema. Unlike the star schema, dimension tables in a snowflake schema can be further normalized and may have relationships with other dimension tables.

## Stacked Area Chart (100 %) (Standard Visual)
A 100% stacked area chart is a variation of the stacked area chart, where the entire area always sums to 100%. It shows the percentage contributions of each component to the overall total over time. This chart is excellent for visualizing and comparing the relative contribution of each component to the total.

## Stacked Area Chart (Standard Visual) 
A stacked area chart shows multiple data series as stacked areas to highlight how the individual components of a total change over time. Each area represents a data series, and the stacked structure helps to show how each series contributes to the overall change. This chart is great for visualizing proportional changes and compositions over time.

## Stacked Bar Chart (100 %) (Standard Visual)
A stacked bar chart (100%) shows the proportion of each subcategory relative to the total category, where the entire bar always equals 100%. Each subcategory is represented in the bar by a different color. This chart is used to display percentage relationships of parts to the whole, making it easy to interpret the percentage share of each subcategory.

## Stacked Bar Chart (Standard Visual)
A stacked bar chart displays the relationships and proportions between multiple data categories using horizontal bars. Each bar represents a total category, which is subdivided into different subcategories, with each subcategory represented by a different color. The stacked bar chart helps visualize the distribution of data in each category and compare the composition of total values.

## Stacked Column Chart (100 %) (Standard Visual)
A stacked column chart (100%) is a vertical version of the stacked bar chart, where the total of each column always adds up to 100%. It shows the percentage contributions of each subcategory to the overall value. This chart is used to visualize the distribution of data within a category and is perfect for comparing the percentage contributions to a total.

## Stacked Column Chart (Standard Visual)
A stacked column chart is similar to the stacked bar chart, but the categories are displayed vertically. Each column represents a total category, which is divided into subcategories. These subcategories are shown in different colors to highlight the proportion and contribution of each category to the overall value. It is ideal for showing the contribution of each subcategory to a total.

## Star Schema
The star schema is a data modeling concept in which a central fact table is linked to one or more dimension tables. The dimension tables are used to filter and group the data in the fact table. These filters and groupings directly affect measures based on the fact table, influencing how key figures are calculated and displayed in reports.



# T

## Table (Standard Visual)
The Table visual in Power BI displays data in a simple row-and-column grid. It is especially useful for detailed analysis, as it can show individual data rows. The table can be sorted, formatted, and enhanced with additional measures. Filters and conditional formatting are also supported.

## Table view
The Table view displays the data in your tables (from your Power BI data model) in a tabular format. It helps verify data, calculated columns, or measures, and supports understanding the underlying contents.

## Tabular Model 
A tabular model is a data model where data is structured and organized into tables. In Power BI, every data model is a tabular model, as data is stored in tables and relationships between these tables are defined.

## Template App (Power BI Service)
A Template App is a pre-built Power BI app that contains a predefined collection of dashboards, reports, and data models, usually provided by Microsoft or third-party vendors. These apps are typically designed for specific industries or use cases and enable quick integration and analysis of data.

## Tile
A tile is a building block of a dashboard in the Power BI service. Tiles can contain visualizations, KPIs, text boxes, images, or even entire report pages sourced from different reports or datasets. They provide a clear way to display information and can be individually formatted and positioned.

## Treemap (Standard Visual)
A treemap visual displays hierarchical data as nested rectangles. Each rectangle represents a category, with its area proportional to the category’s value, and subcategories nested within parent rectangles.

# U 

## Uncomment (DAX query view)
Uncomment is an option in the “Home” tab of the DAX query view in Power BI. It removes the commenting from the selected lines, allowing the DAX code to be executed again. This feature is helpful when reactivating previously disabled code, such as after debugging or testing.

# V  

## VertiPaq 
VertiPaq is the in-memory storage engine used by Power BI. It stores data in a highly compressed, columnar format and is optimized for fast query performance. VertiPaq uses columnstore technology and advanced compression techniques to keep large datasets in memory, allowing for very fast aggregations, filtering, and calculations. To get the best performance from VertiPaq, the data model should be optimized – for example, by reducing unnecessary columns and minimizing cardinality.

## View as (Modeling Tab)
The "View as" option in the "Modeling" tab allows you to view the report as if you were assigned to one or more security roles. This is useful for testing Row-Level Security (RLS) to ensure users only see the data they're authorized to view. You can simulate multiple roles at once or preview the report without any roles applied to see unrestricted data access.

## Visualizations pane
The Visualizations Pane in Power BI Desktop is the right-side panel where you can select visual types, assign data fields, and customize the formatting of the currently selected visual.

# W  

## Waterfall Chart (Standard Visual)
A waterfall chart visualizes the incremental gains and losses from a starting value to an ending value, distinguishing positive, negative, and total steps.

# X  

# Y  

# Z  
