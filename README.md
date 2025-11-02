# 🗺️ The Family Travel Tracker

A full-stack app to log family trips: places, dates, notes, and simple stats.

## 🧠 Stack
- Node.js, Express.js
- EJS templates
- PostgreSQL (CRUD)
- HTML5 / CSS3 (responsive)

## ✨ Features
- Create / edit / delete trips (city/country, dates, notes)
- List + detail pages (EJS)
- Basic search/filter by country or dates
- Server-side validation + error messages
- (Optional) map link for a place

## 🔧 Prerequisites
- Node.js 18+
- PostgreSQL running locally (or cloud)

Create a DB and a simple table:
```sql
CREATE TABLE trips (
  id SERIAL PRIMARY KEY,
  place TEXT NOT NULL,
  country TEXT NOT NULL,
  start_date DATE NOT NULL,
  end_date DATE NOT NULL,
  notes TEXT
);
