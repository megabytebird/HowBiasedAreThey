# HowBiasedAreThey
Web Crawler meets Data Analytics to determine without pre-bias the general sentiment of news outlets and media sources

Current requirements (and references requirements were pulled from):

  
https://www.topcoder.com/thrive/articles/web-crawler-in-python
  pip install beautifulsoup4
  pip install requests
  pip install lxml
  
https://www.postgresqltutorial.com/postgresql-python/connect/
  pip install psycopg2

Current Architecture:
Docker containers running the following:
Postgres DB (TODO)
PGAdmin4 (TODO)
Java Backend with Spring Boot (and potentially liquibase) for DB Management and Data Querying (TODO)
Python Web Scrapers (1 per news service) (TODO)
