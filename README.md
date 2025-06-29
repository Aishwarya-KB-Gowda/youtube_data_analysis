# 📊 YouTube Data Harvesting and Warehousing

A complete data pipeline project using **YouTube Data API**, **MongoDB**, **MySQL**, and **Streamlit** to extract, store, migrate, and visualize YouTube channel data.

---

## 📁 **Project Domain:** Social Media Analytics

---

## 🎯 **Problem Statement**

Develop a Streamlit application that:
✅ Accepts YouTube Channel IDs and extracts channel details using YouTube Data API
✅ Stores raw and semi-structured data in MongoDB (Data Lake)
✅ Allows migration of selected channel data to MySQL (Data Warehouse) in structured form
✅ Provides search functionality through SQL queries with joins to retrieve channel insights
✅ Displays all data and search results in an interactive Streamlit UI

---

## 🚀 **Technologies Used**

* **Python** — Core programming language
* **YouTube Data API (Google API)** — To fetch channel, video, and comment data
* **MongoDB** — Data Lake for semi-structured/raw data storage
* **MySQL** — Data Warehouse for structured, relational storage
* **Streamlit** — To build an interactive web application
* **Pandas** — Data manipulation and display

---

## 🛠️ **Key Features**

✅ Input YouTube Channel ID and extract:

* Channel name, Subscriber count, Video count
* Playlist ID, Video IDs, Likes, Comments

✅ Store up to **10 YouTube channels** data in MongoDB

✅ Migrate selected channel data to MySQL in a structured format

✅ SQL search functionality with table joins to get:

* Channel-level insights
* Video details
* Comments and engagement metrics

✅ Visualize the data and query results within the Streamlit app

---

## 📊 **Project Workflow**

1. **Data Extraction:**

   * Connects to YouTube Data API using Google API client
   * Retrieves details for a provided Channel ID

2. **Data Lake Storage:**

   * Stores extracted JSON data in MongoDB
   * MongoDB used as flexible data lake for unstructured/semi-structured data

3. **Data Migration to Data Warehouse:**

   * Transfers selected channel data from MongoDB to MySQL
   * Data stored in structured tables for efficient querying

4. **Search & Query:**

   * SQL queries with JOIN operations to combine channel, video, and comment data
   * User inputs guide the queries via Streamlit interface

5. **Visualization:**

   * Displays insights, search results, and channel metrics in Streamlit

---

## 💻 **How to Run the Project**

1. Clone the repository
2. Install required Python packages:

```bash
pip install -r requirements.txt
```

3. Configure your:

   * **YouTube API Key**
   * **MongoDB Connection String**
   * **MySQL Database Credentials**

4. Launch the Streamlit app:

```bash
streamlit run youtube_data.py
```

5. Use the interface to:

   * Extract YouTube channel data
   * Store in MongoDB
   * Migrate to MySQL
   * Run SQL queries and view results

---

## 🧩 **Possible Enhancements**

* Add pagination and filters to data tables
* Include more visual charts and graphs
* Automate scheduled data refresh from YouTube
* Enhance error handling for invalid Channel IDs
* Support additional metadata (tags, categories, etc.)

---

## 👩‍💻 **Author**

**Aishwarya K B** — Data enthusiast with interest in building end-to-end data pipelines for social media platforms.

> [GitHub Profile](https://github.com/Aishwarya-KB-Gowda)

