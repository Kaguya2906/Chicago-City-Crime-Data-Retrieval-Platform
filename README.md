# Chicago-City-Crime-Data-Retrieval-Platform
A user-centric searching engine, combining applications of **NoSQL, ETL pipelines, Elasticsearch, MongoDB, Docker, Jupyter and Flask**.
<img width="1034" alt="Screenshot 2023-11-04 at 3 50 09 PM" src="https://github.com/Kaguya2906/Chicago-City-Crime-Data-Retrieval-Platform/assets/38816901/3fc1ccf6-1200-4ac2-a022-f8a982d9ef84">

## Project Overview
Welcome to the repository for my term project for _APAN 5400: Database Management_, taken in the Spring of 2023 at Columbia University. This project showcases my efforts to design and implement a robust ETL (Extract, Transform, Load) pipeline and the architecture of an optimized data warehouse. The primary objective is to handle Big Data applications with a focus on analytics and scalability.

### Context
With the increasing volume of data generated in our digital era, the ability to efficiently process, store, and analyze data becomes paramount. In this project, I leveraged the expansive dataset of Chicago Crime Reports to not only challenge my skills in database management but also to contribute to a broader social good by enhancing crime analysis and prevention strategies.

### Goal
The core aim of this project is to develop a scalable and user-friendly platform dedicated to crime analysis and visualization. By engineering a proficient data processing system, the project intends to serve as a cornerstone in supporting data-driven crime prevention strategies and decision-making processes.

## Data
The [City of Chicago Crimes 2001-present dataset](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2), sourced from [City of Chicago's Open Data Portal](https://data.cityofchicago.org/), reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days. The size (**7million+ records**)  and the richness of this **JSON** dataset provides a solid ground for diverse analytical approaches and deep insights into criminal patterns.

## ETL Pipeline
To accommodate the complexity and volume of the dataset, I designed an ETL pipeline that:
- **Extracts** data from the Chicago Crime Reports using **API**, ensuring high fidelity and consistency.
- **Transforms** the data through **cleaning, normalization, and preparation** steps to optimize it for analytical queries and machine learning applications.
- **Loads** the data into carefully structured data warehouses: **MongoDB** and **Neo4j** within **Docker** Container, which supports high-performance querying and can scale with the ever-growing dataset size.

## Data Warehouse
The data warehouse architecture is thoughtfully constructed to support the storage needs of Big Data while enabling efficient retrieval and analysis. It is designed to:
- House large volumes of data with a schema optimized for the types of queries anticipated by the business use case.
- Provide a stable foundation for both historical analysis and real-time crime data feeds.
- Facilitate the integration of additional datasets in the future to enrich the analytical capabilities of the platform.

## Business Use Case
In alignment with the project's vision, a business use case was defined to guide the data processing system's development. The use case revolves around providing insights that can inform and enhance crime prevention strategies. By tapping into data analytics, stakeholders can **identify crime hotspots**, **temporal trends**, and **effectiveness of law enforcement activities**.

## Technology Stack
The technology stack employed in this project includes:
- Data Storage: 
  - [Neo4j Graph Database](https://neo4j.com/docs/cypher-manual/current/introduction/)
  - [MongoDB](https://pymongo.readthedocs.io/en/stable/tutorial.html)
  - [Docker](https://docs.docker.com/desktop/get-started/)
- ETL Process:
  - [Elasticsearch](https://www.elastic.co/guide/index.html) 
- Front-End:
  - [Flask](https://readthedocs.org/projects/flask/)
  - API Gateway

## How to Use the Platform
- [01 Data Acquisition](https://github.com/Kaguya2906/Chicago-City-Crime-Data-Retrieval-Platform/blob/main/01.%20API%20Gateway%20for%20Scripting%20Data.ipynb): Begin by setting up the API key to download the latest dataset.
- [02 Data Visualization](https://github.com/Kaguya2906/Chicago-City-Crime-Data-Retrieval-Platform/blob/main/02.%20Neo4j%3A%20nodes%20and%20relationships.ipynb): Explore the initial Neo4j graph visualizations to understand the relationships between various dataset variables.
- [03 Back-End Integration](https://github.com/Kaguya2906/Chicago-City-Crime-Data-Retrieval-Platform/blob/main/03.%20Main.ipynb): Detail the setup and use of MongoDB, Elasticsearch, and Flask for data indexing, querying, and API interaction.
- [04 Front-End Interaction](https://github.com/Kaguya2906/Chicago-City-Crime-Data-Retrieval-Platform/blob/main/04.%20Flask.ipynb): Link the main application functions with the Flask web interface.

You may wanna watch the [demo video](https://youtu.be/PdUPiwrZquQ) on my YouTube Chanel, which showcasing the use of flask-based front-end.

## Useful Resources
- [How to create a website with Python Flask](https://chozinthet20602.medium.com/how-to-create-a-website-with-python-flask-5e5e3d54c827)
- [Creating APIs with Python Flask](https://chozinthet20602.medium.com/creating-apis-with-python-flask-96b4bd5fb851)
- [Rest API | Complete Guide on Rest API with Python and Flask](https://neo4j.com/docs/cypher-manual/current/introduction/)
- [Elasticsearch Source Code](https://github.com/elastic/elasticsearch)
- [Datacamp: Introduction to MongoDB in Python](https://app.datacamp.com/learn/courses/introduction-to-using-mongodb-for-data-science-with-python)

## Find Me All Around the Web
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-Profile-informational?style=flat&logo=linkedin&logoColor=white&color=0A66C2)](https://www.linkedin.com/in/lanru-fu-a55376162/)
[![Gmail Badge](https://img.shields.io/badge/Gmail-Email-informational?style=flat&logo=gmail&logoColor=white&color=D14836)](mailto:lanru.2018@gmail.com)
[![Instagram Badge](https://img.shields.io/badge/Instagram-Profile-informational?style=flat&logo=instagram&logoColor=white&color=E4405F)](https://instagram.com/rurus_memo)
[![Discord Badge](https://img.shields.io/badge/Discord-Chat-informational?style=flat&logo=discord&logoColor=white&color=5865F2)](https://discordapp.com/users/yourDiscordID)
