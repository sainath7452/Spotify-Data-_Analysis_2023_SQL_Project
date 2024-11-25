## Spotify Data Analysis Solutions

---

### **A. General Song Information**

#### 1. What are the top 5 most streamed songs in 2023?

```sql
SELECT track_name, streams
FROM spotify
WHERE released_year = 2023
ORDER BY streams DESC
LIMIT 5;
Result Set:

track_name	streams
Ella Baila Sola	725980112
Shakira: Bzrp Music Sessions, Vol. 53	721975598
TQG	618990393
La Bebe - Remix	553634067
Die For You - Remix	518745108
