---
cssClasses: cards, cards-cols-5, cards-2-3, table-max
---
```dataview
TABLE without ID
	("![|100](" + cover +")") as Cover,
	file.link as Title,
	author as Author
FROM "100 Reference notes/Book DB"
WHERE contains(shelves,"Reading Challenge 2023")
SORT dateRead
```
