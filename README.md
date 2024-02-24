# IBM HR Analytics Employee Attrition & Performance In DataBricks Using Spark
Create a report on a high-level design for a **data pipeline** that
could be used to perform your proposed analysis. 

**Note the following:**
1. The pipeline should include stages as appropriate for: ingest, ETL, storage,
analysis/visualisation.
2. The pipeline should be designed for deployment on a single cloud service provider, and
the platforms for each stage should be deployable or available as managed services on
that provider’s infrastructure.

**3.** These may be services that are exclusive to your chosen cloud provider, or they may be
third-party partner services that are available hosted by your chosen cloud provider.
You will need to research the offerings that are available for your chosen provider.

**This design should consider:**
**a.** The original format of the data (e.g. CSV, JSON) and illustration of the data schema.
**b.** Any transformation to be applied to the data as ETL (Extract, Transform, Load)
**c.** Potential analyses and/or visualisations to be performed. Given the focus of this
module, Expecting that analyses will be based on relatively simple filtering, projection
and aggregation, rather than on ML (Machine Learning) algorithms, although there is
no specific restriction on the analyses you can include.
**d.** The key components of the pipeline: for each component you should select a suitable
cloud service (e.g. data store, file system, analytic engine)
**e.** The overall design of your pipeline, illustrated with one or more diagrams
**f.** The purpose of each component/service within your solution and the nature of the
services, including any open-source platforms that the service is based on

The report should be submitted in the form of a Word or PDF document.
=

You should implement a prototype of your pipeline design using Apache Spark within a
**Databricks notebook**. The prototype will be a simplified working representation of your design
concept. As a minimum it should demonstrate the following stages:
**1.** Source data – storage and ingest
**2.** ETL transformations - at least 2 distinct types of transformation
**3** Storage of data for analytics
**4** Query and visualisation – at least 2 distinct non-trivial queries with appropriate
visualisation of results.

You should prepare your complete prototype in the form of a DataBricks notebook, and you
should make use of markdown cells to document your work. The first markdown cell should
contain a descriptive title for your prototype and your name and student number. It is suggested
that you use Python as the programming language for your implementation.
Each processing stage of your pipeline should be represented by one or more executable
notebook cells. Storage within your pipeline may be represented by file storage in the
Databricks filesystem or by in-memory data structures. Your comments at each point should
explain the purpose of the processing, where it fits into the overall data pipeline. It should be
clear in your prototype where it is illustrating data being transferred from a storage platform to
an analytic platform or vice versa.
