Business Case – Recruitment Company Placement Process (Fictional Data)

As part of a strategic initiative to improve visibility and decision-making within a recruitment company's placement process, a comprehensive Power BI dashboard was developed using a fictional dataset. The project involved a full data pipeline, starting with data ingestion from an Excel spreadsheet and followed by robust data transformation and modeling in Power Query.

Data Preparation and Modeling
Using Power Query, raw data was cleaned, transformed, and enriched to ensure consistency and usability across the reporting layers. Key steps included:

Removing inconsistencies and null values.

Splitting and merging columns for optimal data granularity.

Creating date and category dimensions to facilitate filtering and time intelligence analysis.

Normalizing the structure to support a star schema model, enhancing performance and scalability.

Dashboard and Visualizations
The Power BI dashboard was structured to provide actionable insights into each stage of the placement funnel, from initial contact with candidates to final placement and revenue generation. Several DAX measures were crafted to support dynamic and interactive visualizations, including:

Total Revenue = SUM(Placement[Revenue])

Conversion Rate = DIVIDE([Successful Placements], [Total Opportunities])

Top Industries = TOPN(5, VALUES(Industry[Name]), [Total Revenue], DESC)

Key Metrics and KPIs
The dashboard highlights a broad range of performance indicators and operational metrics:

Revenue Analysis: Overall revenue generated per placement and by industry.

Conversion Rate: Ratio of successful placements to total opportunities, visualized across time and sectors.

Industry Profitability: Identification of the most profitable sectors using TOPN functions, aiding in strategic focus.

Funnel Effectiveness: Drop-off rates between recruitment stages and percentage of unsuccessful projects, enabling continuous process optimization.

Project Outcomes Breakdown: Summary cards and charts show the proportion of ongoing, successful, and unsuccessful recruitment efforts.

Business Impact
The result is a fully interactive, user-friendly dashboard that supports the recruitment company’s strategic goals by:

Providing a data-driven overview of the placement pipeline.

Allowing for real-time insights into key revenue streams and bottlenecks.

Supporting KPI monitoring and forecasting with a data model that’s ready for scale.
