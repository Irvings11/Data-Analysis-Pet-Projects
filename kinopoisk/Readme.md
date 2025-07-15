# 🎬 Movie Dataset 2024 — Web Scraped from KinoPoisk.ru

## 📌 Overview

This dataset contains information about films released in **2024**, scraped from **[KinoPoisk.ru](https://www.kinopoisk.ru/)** using **Selenium**.  
It includes key metadata such as title, country, genre, director, cast, audience rating, number of votes, and runtime.

---

## 🛠️ Data Collection

- 📅 **Scraping Date**: [укажи дату]
- 🔧 **Tools Used**: Python + Selenium + pandas
- 🌐 **Source**: [https://www.kinopoisk.ru/lists/movies/year--2024](https://www.kinopoisk.ru/lists/movies/year--2024)
- ⚙️ **Automation**: Scrolling and dynamic content handling via `WebDriverWait`

---

## 🗂 Dataset Structure

| Column         | Description                                       |
|----------------|---------------------------------------------------|
| `Title`        | Movie title                                       |
| `Year`         | Release year (2024)                               |
| `Country`      | Country of origin                                 |
| `Genre`        | Genre (e.g., horror, drama, sci-fi)               |
| `Director`     | Director’s name                                   |
| `Roles`        | Main actors                                       |
| `Rating`       | Audience rating (from KinoPoisk)                 |
| `Count`        | Number of user votes                              |
| `Duration_min` | Movie duration in minutes                         |

---

## 📊 Sample Entries

```text
Title:       Субстанция  
Year:        2024  
Country:     Великобритания  
Genre:       ужасы  
Director:    Корали Фаржа  
Roles:       Деми Мур, Маргарет Куолли  
Rating:      6.5  
Count:       428400  
Duration:    141 мин

🔍 Key Insights
🏆 Top-rated film: Анора — 7.4

🎯 Most voted film: Субстанция — 428,400+ votes

🧟‍♂️ Most common genre: Horror and Drama

⏱️ Longest film: Субстанция — 141 minutes

📈 Potential Use Cases
Recommender systems
Genre popularity trends
Runtime vs. rating analysis
NLP on cast/director names
Visualization dashboards
