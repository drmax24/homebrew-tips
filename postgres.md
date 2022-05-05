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
```

SQL
```
SELECT version();
```
