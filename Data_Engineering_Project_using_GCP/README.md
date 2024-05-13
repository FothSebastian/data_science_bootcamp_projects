# Data Engineering Project for E-Scooter Fleet Management

## Project Overview
This project was developed during a Data Science Bootcamp at WBS CODING SCHOOL, focusing on building and migrating a data pipeline for a hypothetical e-scooter sharing company. The goal was to automate data collection from various sources to optimize the positioning of e-scooters. An in-depth discussion of the project's development and its outcomes can be found in this detailed [Medium article](https://medium.com/@seb.foth/my-very-first-data-engineering-project-using-gcp-5d702814f790).

## Technologies Used
- **Google Cloud Platform (GCP)**: Cloud Functions, Cloud Scheduler
- **Python Libraries**:
  - **BeautifulSoup**: For web scraping.
  - **Pandas**: For data manipulation and analysis.
  - **Requests**: For making API calls.
- **Databases**: MySQL
- **APIs**: OpenWeather, AeroDataBox

## Project Phases
### Phase 1: Local Data Pipeline
- **Web Scraping**: Extracted city data from Wikipedia using BeautifulSoup.
- **API Integration**: Gathered weather and flight data using OpenWeather and AeroDataBox APIs, respectively.

### Phase 2: Cloud Migration
- Migrated the local data pipeline to GCP.
- Employed Cloud Functions for data retrieval and Cloud Scheduler for automation.

## Key Learnings
- Developed skills in automating data pipelines and integrating data into structured databases.
- Gained insights into cloud services and real-time data processing.

## Challenges
- Encountered and overcame multiple challenges in data collection and pipeline automation, enhancing problem-solving skills.

## Future Work
- Enhance data accuracy and expand data sources.
- Implement machine learning models to predict e-scooter demand.

## Quick Links
- [Project Article on Medium](https://medium.com/@seb.foth/my-very-first-data-engineering-project-using-gcp-5d702814f790)
- [Web Scraping Colab Notebook](https://colab.research.google.com/drive/1JH3boC6JCDWlD0jg926i9tGNN1chcZVY?usp=sharing)
- [Weather Data Colab Notebook](https://colab.research.google.com/drive/1XsxYAiegqk1W2e46uKPqeacfev3YArfJ?usp=sharing)
- [Flight Data Colab Notebook](https://colab.research.google.com/drive/1qG_ja0hJaPv8GrJSRvoj8b2bRus-ksu4?usp=sharing)

Feel free to explore the code and collaborate on future enhancements!
