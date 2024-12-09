# Spotify Data Analysis Solutions

This document provides SQL solutions for analyzing Spotify data along with their corresponding result sets.

---

## **A. General Song Information**

### 1.**What are the top 5 most streamed songs in 2023?**
```sql
SELECT track_name, streams
FROM spotify
WHERE released_year = 2023
ORDER BY streams DESC
LIMIT 5;
