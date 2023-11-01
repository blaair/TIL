```
bool is_distinct(int n, int x[]) {
  for (int i = 0; i < n - 1; i++)
    for (int j = i + 1; j < n; j++)
      if (x[i] == x[j])
        return false;
  return true;
}
```
