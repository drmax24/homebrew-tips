Install
```
brew install postgres
brew services start postgresql  
```

Health check
```
brew services list  
psql --version
ps auxwww | grep postgres
lsof -i :5432
```

SQL
```
SELECT version();
```
