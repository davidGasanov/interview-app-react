# Live Coding Assignment: Product Inventory Table

## Overview
Fetch and display product data from the DummyJSON API. Focus on clean code structure, proper state handling, and a readable UI.

**Time:** 45–60 minutes

---

## API
```
GET https://dummyjson.com/products
```
The response type is available in `src/types/products.ts`.

---

## Requirements

### 1. Data Fetching
- Fetch products on page load
- Use `axios` for the request

### 2. Display
Render the results in an MUI `Table` with the following columns:

| Column | Field |
|---|---|
| Title | `title` |
| Category | `category` |
| Price | `price` |
| Availability | `availabilityStatus` |
| Rating | `rating` |

### 3. States to handle
- **Loading** — show an MUI `CircularProgress` (or other loading indicators) while the request is in flight
- **Empty** — show a message if the response contains no products
- **Error** — show an MUI `Alert` if the request fails

---

## Notes
- You may structure your components however you like
- Styling is not evaluated — clarity and correctness are
- Feel free to use MUI's component library freely
