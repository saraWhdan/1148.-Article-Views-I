# 1148.-Article-Views-I
Problem Link: https://leetcode.com/problems/article-views-i/description/?envType=study-plan-v2&envId=top-sql-50
## Solution

```sql
select distinct author_id as id
from views 
where author_id =viewer_id 
order by author_id
