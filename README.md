# lol-meta-analysis
Big data pipeline for analyzing League of Legends meta trends

# League of Legends Meta Analysis Pipeline

## 1. Problem Definition

### Goal
The goal of this project is to analyze League of Legends match data and identify meta trends based on champion pick rates, win rates, and ban rates.

### Problem
In League of Legends, the game meta continuously changes after each patch update.  
Players often struggle to identify which champions are currently strong or effective in different tiers and roles.

This project aims to collect and process large-scale match data to analyze champion performance and discover meta trends.

### Data
The project will use data collected from:

- Riot Games API
- Match history data
- Champion statistics
- Rank tier information
- Pick rate, win rate, and ban rate data

---

## 2. Tech Stack

The following technologies will be used:

- Apache Kafka  
  - Real-time match data streaming

- Apache Spark  
  - Distributed data processing and analysis

- Apache Hive  
  - Data storage and query management

- Python  
  - Data preprocessing and visualization

- GitHub  
  - Version control and collaboration

---

## 3. Implementation Plan

### Step 1. Data Collection
- Collect match data using Riot Games API
- Stream game data through Kafka

### Step 2. Data Storage
- Store collected match records in Hive
- Organize data by patch version and rank tier

### Step 3. Data Processing
- Use Spark to preprocess large-scale match data
- Remove duplicates and handle missing values

### Step 4. Data Analysis
- Analyze champion pick rates, win rates, and ban rates
- Compare champion performance across tiers and patches
- Identify meta changes over time

### Step 5. Visualization
- Visualize champion statistics and trends using Python
- Create graphs and dashboards for analysis results

---

## Expected Outcome

- Identify strong champions in the current meta
- Discover trends across different game patches
- Build a scalable game data analysis pipeline
- Gain experience with big data processing technologies
