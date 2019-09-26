### dateparse
---
https://github.com/araddon/dateparse

```go
// parseany_test.go

func TestOne(t *testing.T) {
  time.Local = time.UTC
  var ts time.Time
  ts = MustParse("2018:09.30")
  assert.Equal(t, "2018-09-30 00:00:00 +0000 UTC", fmt.Sprintf("%v", ts.In(time.UTC)))
}

type dateTest struct {
  in, out, loc string
  err bool
}



```

```
```

```
```


