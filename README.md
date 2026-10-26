# E-commerce Sales Analysis Dashboard

An interactive sales dashboard built with HTML, CSS, JavaScript and Chart.js. It reads the UCI Online Retail dataset (transactions from Dec 2010 to Dec 2011) and shows revenue, orders, customers and countries.

## Features
- KPI cards: total revenue, orders, customers, countries
- Monthly revenue trend chart
- Top countries and top products charts
- Top 10 customers table
- Filters by month, country and product, plus a search box
- Reset button and Export CSV for the filtered data

## How to run
1. Download or clone this repository.
2. Open the folder in VS Code and run it with **Live Server** (right-click `index.html` → Open with Live Server),
   or open a terminal in the folder and run:

 python3 -m http.server 8000

      then open `http://localhost:8000` in your browser.
3. An internet connection is needed for the Chart.js CDN.

Note: do not double-click `index.html`. The browser blocks loading the CSV file without a local server.

## Dataset
UCI Online Retail dataset (`online_retail.csv`). Revenue is calculated as quantity × unit price, so returns (negative quantities) reduce the total.

## Technologies
HTML, CSS, JavaScript, Chart.js

## Author
Nitin Kumar, BTech CSE (AIML), Amity University Jharkhand
