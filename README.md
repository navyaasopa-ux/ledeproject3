# Lede Project 3
# What Scraping 1,000 Books Taught Me

## Overview

This project explores what I learned from scraping and analyzing 1,000 books from a mock e-commerce website. This was done as part of the Lede Data Journalism Program at Columbia University. I've combined web scraping, data analysis, and visual storytelling.

🔗 **Live Project:**
https://navyaasopa-ux.github.io/ledeproject3/

## Summary

Using data scraped from *Books to Scrape*, a sandbox website designed for practicing scraping, this project looked into:

* Book price distribution
* Percentage of books by genres
* Pricing variations across genres
* Ratings based on genres

## Data Source

* Website: https://books.toscrape.com/
* Size: 1,000 books across 50 pages
* Fields collected:

  * Title
  * Genre
  * Price
  * Rating
  * Availability

## Methodology

### 1. Web Scraping

* Used **Python** with **Requests** to fetch pages
* Used **BeautifulSoup** to parse HTML

### 2. Data Cleaning

* Merged inconsistent labels for charts (e.g., “Default” and “Add a comment” → “Uncategorized”)
* Structured data into a clean CSV

### 3. Analysis

* Grouped data by genre and rating using **Pandas**
* Calculated averages and distributions

### 4. Visualization

* Built charts using **Datawrapper**
* Embedded visuals into a custom HTML page

## Tools Used

* Python
* Datawrapper
* HTML & CSS
* GitHub Pages

## Challenges

* Cleaning and standardizing genre data
* Deciding how to group unclear categories
* Translating analysis into lucid visuals

## What I Learned

* How to scrape structured data from multiple pages
* The importance of data cleaning in real-world datasets
* How to identify meaningful patterns in a messy dataset

## Repository

View the full code, data, and notebook here:
https://github.com/navyaasopa-ux/ledeproject3
