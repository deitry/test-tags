test maximum tags number

```powershell
1..1000 |% { git tag "test$_" }
```
