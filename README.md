<h1>GLOBAL GHG EMISSION DATA WAREHOUSE</h1>

<h2>Project Background</h2>

<p>
Greenhouse gas (GHG) emissions have become a pressing global concern, driving governments, researchers, and organizations worldwide to better understand, quantify, and mitigate their impact on climate change. Reliable data is essential for informed policy-making, scientific research, and monitoring progress toward international climate goals.
</p>

<p>
The <strong>Emissions Database for Global Atmospheric Research (EDGAR)</strong> serves as one of the most credible and comprehensive sources of global anthropogenic emissions data. Managed by the European Commission, EDGAR provides consistent and comparable datasets of GHG and air pollutant emissions for every country and sector worldwide. These datasets are shared in the form of detailed Excel spreadsheets containing emission values derived from standardized methodologies and verified sources.
</p>

<p>
However, the structure of EDGAR’s raw Excel files is not optimized for advanced data analysis. To enable efficient querying, integration, and further processing, the data must first be extracted, cleaned, and transformed into a relational format suitable for SQL-based exploration.
</p>

<p>
This project addresses that need by developing a data pipeline that:
</p>

<ul>
  <li>Extracts raw GHG emission data from EDGAR’s published spreadsheets (<a href="link-to-your-spreadsheet-file">available here</a>).</li>
  <li>Transforms the data into a normalized relational structure using <strong>Python</strong>.</li>
  <li>Loads the transformed datasets into a <strong>PostgreSQL</strong> database for scalable storage, querying, and analysis.</li>
</ul>

<p>
Through this process, the project ensures that complex emission data can be handled programmatically and analyzed efficiently — laying a solid foundation for environmental data science, policy evaluation, and global emission trend studies.
</p>

<h2>Project Goal</h2>

<p>
The primary objective of this project is to design and implement an <strong>ETL (Extract, Transform, Load) pipeline</strong> that efficiently converts EDGAR’s raw emission spreadsheets into a structured SQL database. By doing so, the project aims to bridge the gap between raw environmental datasets and analytical readiness.
</p>

<p>Specifically, the project seeks to:</p>

<ul>
  <li>Develop a ETL pipeline capable of extracting emission data directly from EDGAR’s publicly available spreadsheets, transforming it into a clean, consistent schema, and loading it into a PostgreSQL database.</li>
  <li>Deliver a well-structured relational database that supports efficient querying, integration, and statistical analysis — enabling researchers, policymakers, and developers to gain deeper insights into global GHG emission patterns.</li>
</ul>

<p>
Through these goals, the project provides a scalable foundation for environmental data analytics and supports informed decision-making in the pursuit of sustainable development and climate action.
</p>

