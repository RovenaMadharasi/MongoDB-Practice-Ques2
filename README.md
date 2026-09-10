# MongoDB Practice Task — Operators, Update, Delete, Count & Cursor Methods

A set of 20 solved MongoDB exercises on a sample `products` collection, covering comparison and logical query operators, update and delete operations, document counting, and cursor methods like sorting and limiting.

## About

This repository contains a hands-on MongoDB practice task built around a `products` collection (fields like `name`, `price`, `stock`, and `category`). It walks through the core query and data-manipulation operations every MongoDB user needs:

- **Comparison operators** — `$gt`, `$lt`, `$gte`, `$lte`, `$ne` for filtering by price and stock
- **Logical operators** — combining conditions with implicit AND and explicit `$or`
- **Update operations** — `updateOne()` and `updateMany()` with `$set`
- **Delete operations** — `deleteOne()` and `deleteMany()`
- **Count documents** — `countDocuments()` with and without filters
- **Cursor methods** — `sort()` and `limit()` for ordering and restricting results

Each question is paired with a working query, making this a practical reference for anyone learning MongoDB CRUD operations or preparing for a database course/interview.

## Sample Data Structure

```json
{
  "name": "Laptop",
  "price": 799,
  "stock": 25,
  "category": "Electronics"
}
```

## How to Use

1. Set up a local MongoDB instance or a free [MongoDB Atlas](https://www.mongodb.com/atlas) cluster.
2. Create a `products` collection and insert sample documents matching the structure above.
3. Open `mongosh` or MongoDB Compass and run through each query.
4. Try tweaking the filter values or combining operators differently to deepen your understanding.

## Prerequisites

- MongoDB installed locally, or a MongoDB Atlas cluster
- `mongosh` (MongoDB Shell) or MongoDB Compass
- Basic familiarity with JSON/BSON documents

## Contents

| Section | Covers |
|---|---|
| Operators (Q1–8) | `$gt`, `$lt`, `$gte`, `$lte`, `$ne`, equality, category + price filters |
| Logical Operators (Q9–12) | Combining conditions with AND / `$or` |
| Update Operations (Q13–15) | `updateOne()`, `updateMany()`, `$set` |
| Delete Operations (Q16–17) | `deleteOne()`, `deleteMany()` |
| Count Documents (Q18–19) | `countDocuments()` |
| Cursor Methods (Q20) | `sort()`, `limit()` |

