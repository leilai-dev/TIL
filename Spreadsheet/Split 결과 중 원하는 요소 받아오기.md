[google sheets - Get first item from Split() - Stack Overflow] (https://stackoverflow.com/questions/32307788/get-first-item-from-split/32307979)

```
=index(SPLIT("1.23/1.15", "/"), 0, 2)
```

```
=query(SPLIT("1.23/1.15", "/"), "SELECT Col1")
```
