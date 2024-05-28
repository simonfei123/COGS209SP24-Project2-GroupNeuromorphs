## Processed Embeddings
Folder sturcture
```
-- README.md
|- KR_map.csv
|- EN_map.csv
--mapping.csv
```
### KR_map and EN_map
- Description: Distinct Korean and English words with index and embeddings
- Columns: ['KR_id', 'KR_word', 'KR_embedding']
- embedding is a list with 2048 parameters
### mapping.csv
This file include the relationship between Korean and English words. Each word is represented by its index in KR_map and EN_map. There are 1 Korean column and 5 English columns. English columns have `NaN` value