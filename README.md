# Music-Store-Data-Analysis
This project explores a digital music store database using SQL to uncover business insights. By analyzing customer behavior, sales trends, artist popularity, and genre preferences, the project answers key questions that can help the store improve marketing strategies, identify top customers, and make data-driven business decisions.


#  🎶 Music Store Data Analysis (SQL Project)

## 📌 Project Overview

This project analyzes a music store database using SQL. The database contains information about employees, customers, invoices, tracks, playlists, albums, artists, and genres.
The goal is to answer *business-related questions* such as:

* Who are the top customers?
* Which country generates the most revenue?
* What are the most popular genres?
* Which artists earn the most across different countries?

By running SQL queries, we can extract insights for decision-making such as *where to host music festivals, customer spending habits, and genre preferences.*

---

## 🗂 Database Schema

The schema consists of the following tables:

* *Employee*: employee details
* *Customer*: customer details and assigned support reps
* *Invoice*: customer invoices with billing info
* *Invoice\_Line*: line items for each invoice
* *Track*: music tracks with metadata
* *Album*: albums linked to artists
* *Artist*: artist information
* *Genre*: track genres
* *Playlist & Playlist\_Track*: playlists and associated tracks
* *Media\_Type*: audio format

(Schema diagram is included in the repo for quick reference.)

---

## ❓ Business Questions Answered

1. Identify the most senior employee based on job title.
2. Determine which countries generate the most invoices.
3. Find the top 3 highest invoice totals.
4. Identify the city with the highest total invoice revenue (potential music festival location).
5. Find the customer who has spent the most money overall.
6. Retrieve the emails and names of customers who listen to Rock music, sorted by email.
7. Find the top 10 artists with the most Rock tracks in the dataset.
8. List all tracks longer than the average track length (name & duration).
9. Calculate how much each customer has spent on different artists.
10. Find the most popular genre in each country (include ties where applicable).
11. Identify the highest-spending customer(s) in each country.
12. Determine which customers prefer which genres.
13. Find the artists that generated the most revenue in each country.
14. Compare sales across billing countries.
15. Show the distribution of media types sold.

---

## ⚙ Tech Stack

* *SQL* (MySQL)
* *Database Visualization*: Schema diagram provided
* *GitHub*: Project hosting


## 📈 Insights Gained

* The USA generates the most invoices.
* The city with the highest revenue can be a candidate for a music festival.
* Rock is the most popular genre across several countries.
* Certain artists dominate revenue in specific regions.
* Media type distribution shows customer preferences in format.

## 🔮 Future Improvements

* Create data visualizations using Python.
* Build an interactive dashboard.
* Automate queries with stored procedures.

## 🧑‍💻 Author
*Shivam Kumar Jha*
