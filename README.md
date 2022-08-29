# HowBiasedAreThey
Web Crawler meets Data Analytics to determine without pre-bias the general sentiment of news outlets and media sources

Current library dependencies and software requirements (and references requirements were pulled from):

PGAdmin (DB Management)
Postgres (DB Store)
Springboot IDE (Java Development)
Docker (Containerization and Application Deployment)
Notepad++ (Generalized IDE/Text Editing)
Python3 (Web Scraper)
Anaconda (Python Env and Dependency Management)

-------------------------
Python Dependencies
- Pip commands can generally be swapped for conda commands when dealing with dependency installation

https://www.topcoder.com/thrive/articles/web-crawler-in-python
  pip install beautifulsoup4
  pip install requests
  pip install lxml
  
https://www.postgresqltutorial.com/postgresql-python/connect/
  pip install psycopg2

--------------------------
Architecture:

Docker containers running the following:
- Postgres DB (DONE)
- PGAdmin4 (DONE)
- Java Backend with Spring Boot for DB Management (DONE) and Data Querying (TODO)
- Basic Python Web Scrapers (1 per news service) (TODO)
- Basic Sentiment Analyzer (1 per news service) (TODO)
- Cross-Organiation Sentiment Comparison Tool (TODO)
- Advanced Python Web Scrapers (Integrated with advanaced keyword and context analytics algorithms) (TODO)
- Advanced Sentiment Analyzer (Utilizes advanced keyword and context data to provide more accurate and contextualized sentiments) (TODO)
- Live News Analysis Tool (Grabs latest news articles and analyzes sentiment on a real-time basis) (TODO)
